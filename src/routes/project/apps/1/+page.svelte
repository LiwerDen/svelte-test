<main>
    <form on:submit|preventDefault={add}>
        <input bind:value={newItem} placeholder="Enter to-do">
        <button class="add-todo" on:click={add}><span>+</span></button>
    </form>
</main>
<script>
    let newItem = "";
    let todoList = [];
    function add(){
        if (newItem !== ""){
            todoList = [
                ...todoList,
            {
                task:newItem,
                completed:false,
            },
            ];
            newItem = "";
        }
    }
</script>
<style>
    main{
        display: flex;
        flex-direction: column;
        align-items: center;
        min-height: 100%;
        padding: 5vmin;
        box-sizing: border-box;
        background: antiquewhite;
    }
    form{
        width: 100%;
        max-width: 500px;
        display: flex;
        align-items: center;
        margin-bottom: 1rem;
    }
    input{
        flex-grow: 1;
        width: 0;
        border: none;
        border-bottom: 1px solid black;
        background: transparent;
        box-shadow: none;
        font-size: 1.2rem;
        margin: 0;
        outline: none;
    }
</style>