<template>
<!-- component -->
<footer class="flex justify-center px-4 text-gray-100 bg-gray-800">
        <div class="container py-6">
            <h1 class="text-center text-lg font-bold lg:text-2xl">
                Gaukite Nuostabiausia Tinklaraštį
            </h1>

            <div class="flex justify-center mt-6">
                <div class="bg-white rounded-lg">
                    <form @submit.prevent="submit">
                        <div class="flex flex-wrap justify-between md:flex-row">
                            <input for="email"
                            class="m-1 p-2 appearance-none text-gray-700 text-sm focus:outline-none"
                            placeholder="Įveskite Paštą">/>
                            <button type="submit"
                            class="w-full m-1 p-2 text-sm bg-gray-800 rounded-lg font-semibold uppercase lg:w-auto">
                            Prenumeruokite</button>
                        </div>
                    </form>

                </div>
            </div>

            <hr class="h-px mt-6 bg-gray-700 border-none">

            <div class="flex flex-col items-center justify-between mt-6 md:flex-row">
                <div>
                    <a href="#" class="text-xl font-bold">Brand</a>
                </div>
                <div class="flex mt-4 md:m-0">
                    <div class="-mx-4">
                      <a href="/" class="px-4 text-sm">Pagrindinis</a>
                      <a href="/blogs" class="px-4 text-sm">Tinklaraštis</a>
                      <a href="/team" class="px-4 text-sm">Komanda</a>
                  	</div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
  data() {
    return {
      form: {
        email: null,
      },
    }
  },
  methods: {
    submit() {
      this.$inertia.post('/users', this.form)
    },
  },
}
</script>
