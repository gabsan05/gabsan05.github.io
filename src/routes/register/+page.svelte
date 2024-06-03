
<h1>Registration Form</h1>



<script>
    function handleSubmit() {
    console.log('Form submitted!')
    console.log("Hello!"+{name})
    }
    </script>



<form on:submit|preventDefault={handleSubmit}>

    <label>First Name:</label>
    <input id="firstname" type="text"/>
    <label>Last Name:</label>
    <input id="last name" type="text"/>
    <label>Username:</label>
    <input id="username" type="text"/>
    <label>Email:</label>
    <input id="email" type="text"/>
    <label>Password:</label>
    <input id="password" type="text"/>

    <button type="submit">Register</button>

    <p>Have an account? <a

        href="/Log in">Log in</a></p>

</form>

<style>
    form{
        display:grid;
        width: 60vw;
        max-width: 500px;
        min-width: 300px;
    }
</style>

