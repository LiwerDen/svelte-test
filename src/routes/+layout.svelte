<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo" title="Back to Homepage">Liwer Sawmill</a>
        <div class="nav-links">
            {#each nav as link}
                <a href={link.href} class="link">{link.title}</a>
            {/each}
        </div>
    </div>
</nav>

<div class="container">
    <!--Pages will be injected below-->
    <slot></slot>
</div>

<style>
    .container{
        max-width: 1400px;
        margin: 50px auto;
    }
    .nav-links{
        font-weight: 700px;
        font-size: 1rem;
    }
</style>

<script>
    const nav = [
        {
            title: 'Каталог товаров',
            href:'/about',
            isShow: true,
        },
        {
            title: 'Услуги',
            href:'/blog',
            isShow: true,
        },
        {
            title: 'О нас',
            href:'/project',
            isShow: true,
        },
        {
            title: 'Контакты',
            href:'/contact',
            isShow: true,
        },
    ];
</script>