<template>
<div class="contact">
    <h1>Contact Us</h1>
    <br><br>
    <form name="contact" netlify>
        <div class="form-group">
            <label for="inputName4">Namel</label>
            <input type="text" class="form-control" id="inputName4">
        </div><br>
        <div class="form-group">
            <label for="inputEmail4">Email</label>
            <input type="email" class="form-control" id="inputEmail4">
        </div>
        <div class="form-group">
            <label for="inputRole">Role</label>
            <select id="inputRole" class="form-control">
                <option selected>Choose...</option>
                <option name="manager">Manager</option>
                <option name="developer">developer</option>
                <option name="customer">customer</option>
            </select>
        </div><br>
        <div class="form-group">
            <label for="validationTextarea">Textarea</label>
            <textarea class="form-control is-invalid" rows="3" cols="25" id="validationTextarea" placeholder="Required example textarea" required></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Sign in</button>
    </form>
</div>
</template>

<script>
// export default {

// }
</script>

<style scoped>
.contact {
    width: 600px;
    height: auto;
    margin-top: 60px;
    margin-bottom: 90px;
    margin-left: auto;
    margin-right: auto;
}

@media(max-width: 600px) {
    .contact {
        width: 300px;
        height: auto;
        margin-top: 40px;
        margin-bottom: 70px;
        margin-left: auto;
        margin-right: auto;
    }
}
</style>
