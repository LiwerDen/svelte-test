<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo" title="Back to Homepage">Имя Фамилия</a>
        <div class="nav-links">
            <!--{#if link.isShow}
            <a href={link.href} class="link">{link.title}</a>
            {/if}--> 
            <a href="/about" class="link">Обо мне</a>
            <a href="/blog" class="link">Блог</a>
            <a href="/project" class="link">Портфолио</a>
            <a href="/contact" class="link">Контакты</a>
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
</style>

<script>
    const nav = [
        {
            title: 'Обо мне',
            href:'/about',
            isShow: true,
        },
        {
            title: 'Блог',
            href:'/blog',
            isShow: true,
        },
        {
            title: 'Портфолио',
            href:'/project',
            isShow: true,
        },
        {
            title: 'Контакты',
            href:'/contact',
            isShow: true,
        },
        {
            title: 'temp',
            href:'/temp',
            isShow: false,
        },
    ];
</script>