<template>
<div>
    <Card   v-for="(card,index) in cards" 
            :key='index'
            :item="card"/>
</div>
</template>

<script>
import Card from "@/components/Card"

export default {
    components:{
        Card
    },
    data: () => {
        return{
            cards:[
                {
                    title: "product design",
                    description: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet distinctio porro doloremque magnam est praesentium vitae, officia suscipit, commodi omnis sunt recusandae ut laborum rem aliquid deserunt accusamus deleniti repellat.",
                    img: "/proj1/cover.png",
                    open:false
                },
                {
                    title: "yolo design",
                    description: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet distinctio porro doloremque magnam est praesentium vitae, officia suscipit, commodi omnis sunt recusandae ut laborum rem aliquid deserunt accusamus deleniti repellat.",
                    img: "/proj2/cover.png",
                    open:false
                },
            ]
        }
    }

}
</script>

<style>

</style>