<template>
    <div class="w-25">
        <form action="">
            <div class="input-group mb-3 w-100">
                <input v-model="form.title" type="text" class="form-control form-control-lg" placeholder="What do you wanna do?" aria-label="Recipient's username" aria-describedby="button-addon2">
                <div class="input-group-append">
                    <button class="btn btn-success" type="submit" id="button-addon2">Add to your list</button>
                </div>
            </div>
        </form>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                form:new Form({
                    title: '',
                })
            }
        },
        mounted() {
            
        }
    }
</script>
