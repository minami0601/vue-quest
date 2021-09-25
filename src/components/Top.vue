<template>
    <v-container>
        <v-card
        class="my-10"
        elevation="10"
        rounded="xl"
        width="100%"
        >
            <v-container class="mx-10 text-center" >
                <v-form>
                    <v-text-field
                    label="YouTube動画ID"
                    v-model="movieUrl"
                    placeholder="動画URLの【v= 】の後に続く英数字"
                    style="width: 300px"
                    />
                    {{ movieUrl }}
                </v-form>
            </v-container>
        </v-card>
    </v-container>
</template>

<script>
    export default {
        name: 'Top',
        data () {
            return {
                movieUrl: "",
            }
        }
    }
</script>
