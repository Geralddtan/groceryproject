<template>
    <div>
        <h2> Add Item Here! </h2>
        <form> 
            <label class = "Item" type = "text"> Item: </label>
            <input type="text" id="Item" name="Item"><br>
            <label class = "Description" type = "text"> Description: </label>     
            <input type="text" id="Description" name="Description"><br>
        </form>
        <br>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .Item{
        font-weight: bold;
        text-align: left;
    }

    .Description{
        font-weight: bold;
        text-align: left;
    }

</style>