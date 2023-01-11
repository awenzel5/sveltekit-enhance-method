<script>
    import { enhance } from "$app/forms";
</script>
<a href=/method>Go To Method</a>
<form method="POST" use:enhance>
    <label for="name">Name="name"</label>
    <input name="name"/>
    <button type="submit">Submit</button>
</form>