<template>
    <div>
        <slot></slot>
    </div>
</template>

<style scoped> 
    :slotted(img){
        height: 12rem;
        padding: 0.5rem;
        background-color: snow;
    }
    div{
        display: inline-block;
        text-align: center;
        border: 1px solid #f2f2f2;
        padding: 1%;
        border-radius: 5px;
        margin: 4px;
    }
</style>