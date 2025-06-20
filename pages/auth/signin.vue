<template>
    <div>
        <v-container class="d-flex justify-center align-center" style="height: 100vh;">
        
        <v-card max-width="500" class="pa-7">
             <v-card-title>Login Page</v-card-title>
            <v-card-text>
                
                <v-form>
                    <v-text-field
                    
                    outlined
                    
                    label="Email"
                    type=" Email"
                    >
                </v-text-field>
                <v-text-field
                outlined
                label="Password"
                type="Password"
                >

                </v-text-field>
                <v-btn color="primary" type="submit" class="mt-4" block>LOGIN</v-btn>
                </v-form>
            </v-card-text>
        </v-card>
        </v-container>
    </div>
</template>

<script>

export default {
    layout: "auth"

    
}


</script>