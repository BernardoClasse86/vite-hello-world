<template>
    <div class="p-5 text-center bg-image rounded-3"
        style=" background-image: url('https://mdbcdn.b-cdn.net/img/new/slides/041.webp'); height: 400px;">

        <div class="mask" style="background-color: rgba(0, 0, 0, 0.6);">

            <div class="d-flex justify-content-center align-items-center h-100">

                <div class="text-white">

                    <h1 class="mb-3">{{ jumboTitle }}</h1>

                    <h4 class="mb-3">{{ jumboText }}</h4>

                </div>

            </div>

        </div>

    </div>
</template>

<script>
export default {

    data() {

        return {

            jumboTitle: 'Jumbotron',
            jumboText: 'Questo e il mio primo jumbotron'

        }

    }

}
</script>