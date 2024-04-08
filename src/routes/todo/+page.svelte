<script>
   let tasks = [];
   let completedTasks = [];
   let newTask = '';

    

    function addTask() {
        if (newTask.trim() !== '') {
            tasks = [...tasks, newTask];
            newTask = ''; 
        }
    }

    function completeTask(id) {
        const taskIndex = tasks.findIndex(task => task.id === id);
        if (taskIndex !== -1) {
            completedTasks = [...completedTasks, tasks[taskIndex]];
            tasks.splice(taskIndex, 1);
        }
    }

    function removeCompletedTask(id) {
        completedTasks = completedTasks.filter(task => task.id !== id);
    }

</script>

<div class="container">

    <h1>TODO LIST</h1>
    <h2>Uppgifter </h2>
    <input type="text" bind:value={newTask} placeholder="Enter a new task">
    <button on:click={addTask}>Add Task</button>
        

    <div class="layout">

        <div style="display:grid">
        <h1>NEW</h1>

        <ol>
            {#each tasks as task}
            <li>{task}<button on:click={() => completeTask(task.id)}>Completed</button></li>
        {/each} 
        </ol>

        </div>

        <div style="display:grid">
        <h1>COMPLETED</h1>

        <ol>
            {#each completedTasks as task (task.id)}
            <li>{task} <button on:click={() => removeCompletedTask(task.id)}>Remove</button></li>
        {/each}
        </ol>

        </div>
    </div>

    </div>

<style>
    .container{
        width:80vw;
        height:70vh;
        background-color:gray;
        padding-top:10px;
        padding-left:10px;
        border-width:10px;
        border-color:black;
        border-style: groove;
    }
    .layout{
        display: grid;
        grid-template-columns: 50% 50%;
    }
</style>
