<template>
    <section class="WorkCase">
        <h1 class="categorie">Work & Case Studies</h1>
        <div class="container">
            
        </div>

        <div class="card-container">
            
            <div class="card-holder">
                <transition name="img-anim">
                    <div class="animate" v-show="show">
                        <div @click="show = !show" style="text-decoration:none " 
                                class="company" 
                                href="">
                    
                            
                                <p class="metier">Product design</p>
                                <h2 class="name">Smartimer of galaxy</h2>
                                <p class='shorttext'>Workflow and project management together in a timer</p>
                            
                        </div>
                    </div> 
                </transition>
                <a  style="text-decoration:none" 
                    class="company" 
                    href="">
                    <p class="metier">Product design</p>
                    <h2 class="name">smartimer of galaxy</h2>
                    <p class='shorttext'>Workflow</p>
                </a> 
                <a  style="text-decoration:none" 
                    class="company" 
                    href="">
                    <p class="metier">Product design</p>
                    <h2 class="name">smartimer of galaxy</h2>
                    <p class='shorttext'>Workflow</p>
                </a> 
                
                <a class="company" href="#microsoft-interns"></a> 
                <a class="company" href="#amazon-interns"></a> 
                <a class="company" href="#intuit-interns"></a> 
                <a class="company" href="#linkedin-interns"></a> 
                <a class="company" href="#adobe-interns"></a> 
                <a class="company" href="#airbnb-interns"></a> 
                <a class="company" href="#lyft-interns"></a> 
                <a class="company" href="#uber-interns"></a> 
                <a class="company" href="#twitter-interns"></a> 
                <a class="company" href="#shopify-interns"></a> 
                <a class="company" href="#paypal-interns"></a> 
                <a class="company" href="#atlassian-interns"></a> 
                <a class="company" href="#mailchimp-interns"></a> 
                <a class="company" href="#dropbox-interns"></a> 

            </div>
        </div>

    </section>
</template>

<script>
export default {
    data () {
        return {
        show: true
        }
    }
}
</script>

<style scoped>

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

        .card-container {
            margin:auto;
            max-width:1100px;

        }
        .card-holder {
            margin-top:80px;
            grid-template-columns: 1fr ;
            grid-gap: 3rem;
            padding-left: 5%;
            padding-right: 5%;
        }

        .card-holder {
	        display: grid;
            grid-auto-rows: 500px;
            grid-gap: 2.8rem;
        }

       

        .company:nth-child(1) {
            background-image: url('../../assets/proj1/cover.png');
        }

        .company:nth-child(2) {
            background-image: url('../../assets/proj2/cover.png');
            

        }

        .company:nth-child(3) {
            background-image: url('../../assets/proj3/cover.png');
            
        }





    .container *{
        margin: auto;
    }

    .company{
        background-color: #ffffff;
        width: 90vw;
        height: 65vh;
        border-radius: 15px;
        overflow: hidden;
        background-size: auto 100%;
        background-repeat:no-repeat;
        background-position: center top;
        transition: all 0.3s ease-out;
        box-shadow: 0 14px 100px -1px rgba(109, 109, 109, 0.29);
    }
    .company img{
        max-height: 50vh ;
        text-align: center;
        display: block;
    }


    
    .WorkCase{
        margin-top: 5vh;
    }
    .categorie{
        text-align: left;
        margin-left: 5vw;
        font-size:2rem;
    }
    
</style>