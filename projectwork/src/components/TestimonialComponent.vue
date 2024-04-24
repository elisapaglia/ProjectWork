<template>
    <div id="testimonial">
        <hr>
        <h6 class="text-center pb-4 text-uppercase">what clients say</h6>
        <h2 class="text-center pb-5">Testimonial</h2>

        <!--slider-->
        <div class="slider-container d-flex">
            <div class="slider d-flex flex-nowrap mx-auto">
                <!--first slide-->
                <div class="slide active">
                    <div class="container-fluid d-flex mx-auto">
                        <div class="d-flex flex-row justify-content-center pb-5">
                            <!--card with image-->
                            <div class="card1 text-center w-50 p-4">
                                <div class="img-wrapper">
                                    <img src="../assets/final-home--1st.png" class="card-img-top mx-auto mt-4"
                                        alt="ragazzo pelato con gli occhiali">
                                </div>
                                <div class="card-body text-start ms-4 mt-4">
                                    <span class="text-uppercase">rainbow-themes</span>
                                    <h3 class="mt-2">Nevine Acotanza</h3>
                                    <h6>Chief Operating Officer</h6>
                                </div>
                            </div>
                            <hr class="hr-blurry">
                            <!--card with text-->
                            <div class="w-50">
                                <!--buttons-->
                                <div class="d-flex justify-content-end mt-4" id="bottoni-slider">
                                    <button class="prev me-4" id="prevSlide">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="bi bi-arrow-left"
                                            viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M15 8a.5.5 0 0 0-.5-.5H2.707l3.147-3.146a.5.5 0 1 0-.708-.708l-4 4a.5.5 0 0 0 0 .708l4 4a.5.5 0 0 0 .708-.708L2.707 8.5H14.5A.5.5 0 0 0 15 8" />
                                        </svg>
                                    </button>
                                    <button class="next me-4" id="nextSlide">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="bi bi-arrow-right"
                                            viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
                                        </svg>
                                    </button>
                                </div>
                                <!--text-->
                                <div class="mt-5" id="presentation">
                                    <div class="d-flex flex-nowrap w-100">
                                        <div class="d-inline-block mt-3 pt-5 ps-3">
                                            <h4 class="fs-2 fw-bold">Android App Development</h4>
                                            <h6 class="lh-base">via Upwork - Mar 4, 2015 - Aug 30, 2021</h6>
                                        </div>
                                        <div class="d-inline-block mt-5 py-3" id="stars">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                        </div>
                                    </div>
                                    <hr class="mx-auto">
                                    <p class="p-3">Maecenas finibus nec sem ut imperdiet. Ut tincidunt est
                                        ac dolor aliquam sodales. Phasellus sed mauris hendrerit, laoreet sem in,
                                        lobortis mauris hendrerit andte. Ut tincidunt est ac dolor aliquam sodales
                                        phasellus smauris.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!--second slide-->
                <div class="slide">
                    <div class="container-fluid d-flex mx-auto">
                        <div class="d-flex flex-row justify-content-center pb-5">
                            <!--card with image-->
                            <div class="card1 text-center w-50 p-4">
                                <div class="img-wrapper">
                                    <img src="../assets/final-home--2nd.png" class="card-img-top mx-auto mt-4"
                                        alt="ragazzo pelato con gli occhiali">
                                </div>
                                <div class="card-body text-start ms-4 mt-4">
                                    <span class="text-uppercase">bound-trolola</span>
                                    <h3 class="mt-2">Jone Duone Joe </h3>
                                    <h6>Operating Officer</h6>
                                </div>
                            </div>
                            <hr class="hr-blurry">
                            <!--card with text-->
                            <div class="w-50" id="presentation">
                                <!--buttons-->
                                <div class="d-flex justify-content-end mt-4">
                                    <button class="prev me-4" id="prevSlide">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="bi bi-arrow-left"
                                            viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M15 8a.5.5 0 0 0-.5-.5H2.707l3.147-3.146a.5.5 0 1 0-.708-.708l-4 4a.5.5 0 0 0 0 .708l4 4a.5.5 0 0 0 .708-.708L2.707 8.5H14.5A.5.5 0 0 0 15 8" />
                                        </svg>
                                    </button>
                                    <button class="next me-4" id="nextSlide">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="bi bi-arrow-right"
                                            viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
                                        </svg>
                                    </button>
                                </div>
                                <!--text-->
                                <div class="p-4 mt-5 pt-3">
                                    <div class="d-flex flex-nowrap w-100">
                                        <div class="d-inline-block ps-3">
                                            <h4 class="fs-2 fw-bold">Web App Development</h4>
                                            <h6 class="lh-base">Upwork - Mar 4, 2016 - Aug 30, 2021</h6>
                                        </div>
                                        <div class="d-inline-block py-3 ps-4" id="stars">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                        </div>
                                    </div>
                                    <hr class="mx-auto">
                                    <p class="p-3">Maecenas finibus nec sem ut imperdiet. Ut tincidunt est
                                        ac dolor aliquam sodales. Phasellus sed mauris hendrerit, laoreet sem in,
                                        lobortis mauris hendrerit andte. Ut tincidunt est ac dolor aliquam sodales
                                        phasellus smauris.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!--third slide-->
                <div class="slide">
                    <div class="container-fluid d-flex mx-auto">
                        <div class="d-flex flex-row justify-content-center pb-5">
                            <!--card with image-->
                            <div class="card1 text-center w-50 p-4">
                                <div class="img-wrapper">
                                    <img src="../assets/final-home--3rd.png" class="card-img-top mx-auto mt-4"
                                        alt="ragazzo pelato con gli occhiali">
                                </div>
                                <div class="card-body text-start ms-4 mt-4">
                                    <span class="text-uppercase">glassfisom</span>
                                    <h3 class="mt-2">Nevine Dhawan</h3>
                                    <h6>CEO of Officer</h6>
                                </div>
                            </div>
                            <hr class="hr-blurry">
                            <!--card with text-->
                            <div class="w-50" id="presentation">
                                <!--buttons-->
                                <div class="d-flex justify-content-end mt-4">
                                    <button class="prev me-4" id="prevSlide">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="bi bi-arrow-left"
                                            viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M15 8a.5.5 0 0 0-.5-.5H2.707l3.147-3.146a.5.5 0 1 0-.708-.708l-4 4a.5.5 0 0 0 0 .708l4 4a.5.5 0 0 0 .708-.708L2.707 8.5H14.5A.5.5 0 0 0 15 8" />
                                        </svg>
                                    </button>
                                    <button class="next me-4" id="nextSlide">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="bi bi-arrow-right"
                                            viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
                                        </svg>
                                    </button>
                                </div>
                                <!--text-->
                                <div class="p-4 mt-5 pt-3">
                                    <div class="d-flex flex-nowrap w-100">
                                        <div class="d-inline-block ps-3">
                                            <h4 class="fs-2 fw-bold">Android App Design</h4>
                                            <h6 class="lh-base">Fiver - Mar 4, 2015 - Aug 30, 2021</h6>
                                        </div>
                                        <div class="d-inline-block py-3 ps-4" id="stars">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                        </div>
                                    </div>
                                    <hr class="mx-auto">
                                    <p class="p-3">Maecenas finibus nec sem ut imperdiet. Ut tincidunt est
                                        ac dolor aliquam sodales. Phasellus sed mauris hendrerit, laoreet sem in,
                                        lobortis mauris hendrerit andte. Ut tincidunt est ac dolor aliquam sodales
                                        phasellus smauris.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!--fourth slide-->
                <div class="slide">
                    <div class="container-fluid d-flex mx-auto">
                        <div class="d-flex flex-row justify-content-center pb-5">
                            <!--card with image-->
                            <div class="card1 text-center w-50 p-4">
                                <div class="img-wrapper">
                                    <img src="../assets/final-home--4th.png" class="card-img-top mx-auto mt-4"
                                        alt="ragazzo pelato con gli occhiali">
                                </div>
                                <div class="card-body text-start ms-4 mt-4">
                                    <span class="text-uppercase">ncd - design</span>
                                    <h3 class="mt-2">Mevine Thoda</h3>
                                    <h6>Marketing Officer</h6>
                                </div>
                            </div>
                            <hr class="hr-blurry">
                            <!--card with text-->
                            <div class="w-50" id="presentation">
                                <!--buttons-->
                                <div class="d-flex justify-content-end mt-4">
                                    <button class="prev me-4" id="prevSlide">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="bi bi-arrow-left"
                                            viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M15 8a.5.5 0 0 0-.5-.5H2.707l3.147-3.146a.5.5 0 1 0-.708-.708l-4 4a.5.5 0 0 0 0 .708l4 4a.5.5 0 0 0 .708-.708L2.707 8.5H14.5A.5.5 0 0 0 15 8" />
                                        </svg>
                                    </button>
                                    <button class="next me-4" id="nextSlide">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="bi bi-arrow-right"
                                            viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
                                        </svg>
                                    </button>
                                </div>
                                <!--text-->
                                <div class="p-4 mt-5 pt-3">
                                    <div class="d-flex flex-nowrap w-100">
                                        <div class="d-inline-block ps-3">
                                            <h4 class="fs-2 fw-bold">CEO - Marketing</h4>
                                            <h6 class="lh-base">Thoda Department - Mar 4, 2018 - Aug 30, 2021</h6>
                                        </div>
                                        <div class="d-inline-block py-3 ps-4" id="stars">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                        </div>
                                    </div>
                                    <hr class="mx-auto">
                                    <p class="p-3">Maecenas finibus nec sem ut imperdiet. Ut tincidunt est
                                        ac dolor aliquam sodales. Phasellus sed mauris hendrerit, laoreet sem in,
                                        lobortis mauris hendrerit andte. Ut tincidunt est ac dolor aliquam sodales
                                        phasellus smauris.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!--fifth slide-->
                <div class="slide">
                    <div class="container-fluid d-flex mx-auto">
                        <div class="d-flex flex-row justify-content-center pb-5">
                            <!--card with image-->
                            <div class="card1 text-center w-50 p-4">
                                <div class="img-wrapper">
                                    <img src="../assets/final-home--5th.png" class="card-img-top mx-auto mt-4"
                                        alt="ragazzo pelato con gli occhiali">
                                </div>
                                <div class="card-body text-start ms-4 mt-4">
                                    <span class="text-uppercase">default name</span>
                                    <h3 class="mt-2">Davei Luace</h3>
                                    <h6>Chief Operating Manager</h6>
                                </div>
                            </div>
                            <hr class="hr-blurry">
                            <!--card with text-->
                            <div class="w-50" id="presentation">
                                <!--buttons-->
                                <div class="d-flex justify-content-end mt-4">
                                    <button class="prev me-4" id="prevSlide">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="bi bi-arrow-left"
                                            viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M15 8a.5.5 0 0 0-.5-.5H2.707l3.147-3.146a.5.5 0 1 0-.708-.708l-4 4a.5.5 0 0 0 0 .708l4 4a.5.5 0 0 0 .708-.708L2.707 8.5H14.5A.5.5 0 0 0 15 8" />
                                        </svg>
                                    </button>
                                    <button class="next me-4" id="nextSlide">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="bi bi-arrow-right"
                                            viewBox="0 0 16 16">
                                            <path fill-rule="evenodd"
                                                d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8" />
                                        </svg>
                                    </button>
                                </div>
                                <!--text-->
                                <div class="p-4 mt-5 pt-3">
                                    <div class="d-flex flex-nowrap w-100">
                                        <div class="d-inline-block ps-3">
                                            <h4 class="fs-2 fw-bold">Android App Development</h4>
                                            <h6 class="lh-base">via Upwork - Mar 4, 2015 - Aug 30, 2021</h6>
                                        </div>
                                        <div class="d-inline-block py-3 ps-4" id="stars">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill me-1" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                                fill="#FF8F3C" class="bi bi-star-fill" viewBox="0 0 16 16">
                                                <path
                                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                                            </svg>
                                        </div>
                                    </div>
                                    <hr class="mx-auto">
                                    <p class="p-3">Maecenas finibus nec sem ut imperdiet. Ut tincidunt est
                                        ac dolor aliquam sodales. Phasellus sed mauris hendrerit, laoreet sem in,
                                        lobortis mauris hendrerit andte. Ut tincidunt est ac dolor aliquam sodales
                                        phasellus smauris.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!--dots-->
                <div class="dot-container" id="dots-container"></div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'TestimonialComponent',
}


</script>

<style scoped>
* {
    background-color: #212529;
    margin-top: 0;
    color: #c4cfde;
}

#testimonial {
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
    color: #ff014f;
    padding-top: 80px;
}

h2 {
    font-family: 'Montserrat', sans serif;
    font-size: 60px;
    font-weight: 700;
    color: #c4cfde;
}

.slider-container {
    position: relative;
    overflow: hidden;
}

.slider {
    width: 70%;
}

.slide {
    min-width: 100%;
    display: none;
}

.slide.active {
    display: block;
}

.dot-container {
    position: absolute;
    bottom: 10px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
}

.dot {
    width: 20px;
    height: 20px;
    border-radius: 50%;
    background-color: 1px 4px 2px -3px rgba(0, 0, 0, 0.7) inset, -1px -3px 3px -2px rgba(255, 255, 255, 0.2) inset;
    margin: 0 10px;
}

.dot.active {
    background-color: #ff014f;
}

.card1,
#presentation,
#presentation button {
    box-sizing: border-box;
    box-shadow: 10px 10px 19px #1c1e22, -10px -10px 19px #262a2e;
}

.img-wrapper {
    width: 100%;
    overflow: hidden;
    border-radius: 10px;
    margin-bottom: 27px;
}

.card-body span {
    color: #ff014f;
}

.card1 h6 {
    color: #c4cfde;
    font-size: 15px;
    font-weight: 400;
    padding-top: 25px;
}

#presentation {
    border-radius: 15px;
    padding: 25px;
    background-color: linear-gradient(145deg, #1e2024, #23272b);
}

#bottoni-slider button {
    border-radius: 15px;
}

#bottoni-slider button svg {
    width: 30px;
    height: 30px;
    margin: 20px;
    fill: #c4cfde;
}

#presentation h6 {
    color: #c4cfde;
    font-size: 15px;
    font-weight: 600;
    padding-top: 20px;
    padding-bottom: 20px;
}

p {
    font-size: 20px;
}
</style>