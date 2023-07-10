<template>
    <App>
        <h1 class="h3 mb-4 text-gray-800">Add Transaction</h1>

        <div class="content">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-8 mx-auto">
                        <div class="card card-primary">
                            <div class="card-header">
                                <h3 class="card-title">New Contact</h3>
                            </div>
                            <!-- <form @submit.prevent="submitForm"> -->
                            <div class="card-body">

                                <div class="form-group">
                                    <label>First Name</label>
                                    <input type="text" class="form-control">

                                </div>
                            </div>

                            <div class="card-footer">
                                <div class="float-right">
                                    <button type="submit" class="btn btn-primary">Save</button>
                                </div>
                            </div>
                            <!-- </form> -->
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </App>
</template>

<script setup lang="ts">
import App from "@/components/App.vue"
import "@/assets/vendor/bootstrap/js/bootstrap.bundle.min.js"
import "@/assets/vendor/jquery-easing/jquery.easing.min.js"
import "@/assets/js/sb-admin-2.min.js"
</script>

<style scoped></style>
