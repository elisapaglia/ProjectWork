<template>
    <div id="clients">
        <hr>
        <h6 class="pb-4 mt-5 pt-5 ps-5 text-start">POPULAR CLIENTS</h6>
        <h2 class="pb-5 ps-5 text-start">Awesome Clients</h2>

        <div class="row justify-content-center w-100">
            <div class="col-4 ms-5 ps-5 mx-auto align-center">
                <div class="btn-group-vertical" role="group" aria-label="Vertical button group">
                    <button type="button" class="btn" @click="activeTab = 'tab1'">Javascript</button>
                    <button type="button" class="btn" @click="activeTab = 'tab2'">Product design</button>
                    <button type="button" class="btn" @click="activeTab = 'tab1'">Wordpress</button>
                    <button type="button" class="btn" @click="activeTab = 'tab2'">HTML to React</button>
                    <button type="button" class="btn" @click="activeTab = 'tab1'">React to Lavarel</button>
                    <button type="button" class="btn" @click="activeTab = 'tab2'">Python</button>
                </div>
            </div>
            <div class="tab-content col justify-content-start w-100">
                <p :class="{ active: activeTab === 'tab1' }">
                    <!--first line-->
                    <div class="row d-flex flex-nowrap">
                        <div class="card">
                            <div class="card-body text-center">
                                <img src="../assets/client1.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">John Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client2.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Smith Mart</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4 pt-4">
                            <div class="card-body text-center">
                                <img src="../assets/client3.png" alt="logo1" class="pb-2">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Add Dev</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!--second line-->
                    <div class="row d-flex flex-nowrap mt-4">
                        <div class="card">
                            <div class="card-body text-center">
                                <img src="../assets/client4.png" alt="logo1" class="pt-3">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Jone Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client1.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">John Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client2.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Adon Smith</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!--third line-->
                    <div class="row d-flex flex-nowrap mt-4">
                        <div class="card">
                            <div class="card-body text-center">
                                <img src="../assets/client1.png" alt="logo1" class="pt-3">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Jone Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client2.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">John Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client1.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Adon Smith</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!--fourth line-->
                    <div class="row d-flex flex-nowrap mt-4">
                        <div class="card">
                            <div class="card-body text-center">
                                <img src="../assets/client2.png" alt="logo1" class="pt-3">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Jone Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client1.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">John Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client3.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Adon Smith</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                </p>
                <p :class="{ active: activeTab === 'tab2' }">
                    <!--first line-->
                    <div class="row d-flex flex-nowrap mt-4">
                        <div class="card">
                            <div class="card-body text-center">
                                <img src="../assets/client1.png" alt="logo1" class="pt-3">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Jone Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client2.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">John Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client1.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Adon Smith</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!--second line-->
                    <div class="row d-flex flex-nowrap mt-4">
                        <div class="card">
                            <div class="card-body text-center">
                                <img src="../assets/client2.png" alt="logo1" class="pt-3">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Jone Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client1.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">John Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client3.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Adon Smith</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!--third line-->
                    <div class="row d-flex flex-nowrap">
                        <div class="card">
                            <div class="card-body text-center">
                                <img src="../assets/client1.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">John Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client2.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Smith Mart</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4 pt-4">
                            <div class="card-body text-center">
                                <img src="../assets/client3.png" alt="logo1" class="pb-2">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Add Dev</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!--fourth line-->
                    <div class="row d-flex flex-nowrap">
                        <div class="card">
                            <div class="card-body text-center">
                                <img src="../assets/client1.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">John Due</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4">
                            <div class="card-body text-center">
                                <img src="../assets/client2.png" alt="logo1">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Smith Mart</h5>
                                </div>
                            </div>
                        </div>
                        <div class="card ms-4 pt-4">
                            <div class="card-body text-center">
                                <img src="../assets/client3.png" alt="logo1" class="pb-2">
                                <div>
                                    <hr class="mb-4">
                                    <h5 class="card-title">Add Dev</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ClientsComponent',
    data() {
        return {
            activeTab: 'tab1'
        };
    }
}
</script>

<style scoped>
#clients {
    background-color: #212529;
    margin-top: 0;
    margin-bottom: 0;
    padding-right: 50px;
    padding-left: 50px;
    padding-bottom: 100px;
}

hr {
    color: black;
    align-items: center;
    margin-top: 0;
    margin-left: 15px;
    margin-right: 15px;
}

h6 {
    text-transform: uppercase;
    color: #ff014f;
    margin-left: 50px;
}

h2 {
    font-family: 'Montserrat', sans serif;
    font-size: 60px;
    font-weight: 700;
    color: #c4cfde;
    margin-left: 50px;
}

.btn {
    color: #c4cfde;
    font-size: 20px;
    font-weight: 500;
    background-color: #212529;
    box-shadow: 10px 10px 19px #1c1e22, -10px -10px 19px #262a2e;
    padding-top: 30px;
    padding-bottom: 30px;
    padding-left: 80px;
    padding-right: 80px;
}

.btn:hover {
    color: #ff014f;
}

.tab-content>p {
    display: none;
}

.tab-content>p.active {
    display: block;
}

.card {
    width: 250px;
    color: #c4cfde;
    box-sizing: border-box;
    background-color: #2125290e;
    box-shadow: 10px 10px 19px #1c1e22, -10px -10px 19px #262a2e;
    border: none;
    border-radius: 15px;
}

img {
    max-height: 90px;
    margin-top: 40px;
    margin-bottom: 50px;
}

.card-title,
.card hr {
    color: #c4cfde;
    opacity: 30%;
    font-size: 20px;
    font-weight: 400;
}
</style>