<template>
    <div>

        <!-- Hero -->
        <section class=" m:py-8 py-3">

            <Carousel />
        </section>

        <!-- Why Choose Us -->
        <section>
            <div>
                <WhyUs />
            </div>
        </section>

        <!-- Categories -->
        <section>
            <div class="md:pt-20 pt-10 flex flex-col gap-3 justify-center items-center text-center px-2">

                <h1 class="md:text-4xl text-xl text-ebonyClay font-semibold">
                    Current Exams
                </h1>
                <span class="text-ebonyClay text-sm">
                    Followings are exams that are currently active for candidates preparation
                </span>

            </div>
            <div class="py-16">

                <Categories />

            </div>
        </section>

        <!-- Stats -->
        <section class="">

            <Stats />

        </section>

        <!-- Feature -->
        <section>
            <div class="py-16">

                <!-- Typo/Info -->

                <!-- Feature Tabs -->
                <MainFeatures />

            </div>
        </section>


        <!-- Testimonials -->
        <section class=" bg-selago relative">


            <Testimonials />

        </section>


    </div>
</template>
