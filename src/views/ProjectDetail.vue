<template>
    <div class="card-holder">
        <router-link to="/" style="text-decoration:none " 
                    class="company" 
                    href="">
                    <p class="metier">Product design</p>
                    <h2 class="name">Smartimer of galaxy</h2>
                    <p class='shorttext'>Workflow and project management together in a timer</p>
        </router-link> 
        
  </div>
</template>

<script>

import Header from '@/components/project/Proj1.vue'
export default {

}
</script>

<style>

        .company *{
            color: white;
            text-decoration:none;
            text-align: left;
            padding-left:20px;
            padding-right:20px;
        }
        .company .metier{
            font-family: 'Work Sans', sans-serif;
            font-weight: 500;
            font-size: 1rem; 
            text-transform: uppercase;
            color: rgba(255,255,255, 0.7)
        }
        .company .name{
            text-transform: capitalize;
            font-size: 1.4rem; 
            padding-top: 0;
            margin-top:0;
        }
        .company .shorttext{ 
            font-family: 'Work Sans', sans-serif;
            font-size: 1rem; 
            padding-top: 65%
        }
        .card-holder {
            margin-top:0px;
            grid-template-columns: 1fr ;
            padding-left: 0px;
            padding-right: 0px;
        }

        .card-holder {
	        display: grid;
            grid-auto-rows: 100%;
        }

       

        .company:nth-child(1) {
            background-image: url('../assets/proj1/cover.png');
        }





    .container *{
        margin: auto;
    }

    .company{
        background-color: #ffffff;
        width: 100vw;
        height: 80vh;
        border-radius: 0px;
        overflow: hidden;
        background-size: auto 100%;
        background-repeat:no-repeat;
        background-position: center;
        transition: all 0.3s ease-out;
        box-shadow: 0 14px 100px -1px rgba(109, 109, 109, 0.29);
    }
    .company img{
        max-height: 50vh ;
        text-align: center;
        display: block;
    }
</style>