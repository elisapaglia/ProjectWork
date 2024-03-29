<template>
    <div class="container">
        <div class="row">
            <div class="col-5 col-md-3">
                <h5>Pricing</h5>
                <h1>My Pricing</h1>
            </div>
            <div class="col-7 col-md-3">
                
            </div>    
        </div>
    </div>
</template>

<script>
    export default {
        name: 'PricingComponent'
    }
</script>

<style scoped>
* {
    background-color: #212428;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container {  
    display: flex;
    justify-content: center;
    background-color: #212428;
    width: 100%;
    height: 1549px;
}

.row {
    margin: 0;
    width: 100%;
    height: 100%;
    padding-top: 50px;
    padding-left: 5px;
}

h1,h5 {
    display: flex;
    position: fixed;
    font-family: 'Montserrat', sans-serif;
    letter-spacing: 1px;
    text-align: left;
    padding-top: 100px;
    padding-left: 107px;
}

h5 {
    color:#d60547 ;
    text-transform: uppercase;
    font-size: 15px;
    font-weight: 500;
    line-height: 32px;
}    

h1 {
    color: white;
    font-size: 60px;
    font-weight: 700;
    line-height: 72px;
}
</style>