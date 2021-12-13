<template>



<div>
    <div >
        <Headers></Headers>
    </div>

    <div >
        
    </div>

    <div>
        <Footer></Footer>
    </div>

</div>

</template>

<script>
import Headers from '@/Shared/Headers'
import Footer from '@/Shared/Footer'
import AboutQnA from '@/Shared/About/AboutQnA'

export default {
  metaInfo: { title: 'About' },
  components: {
    Headers,
    AboutQnA,
    Footer,
  },
}
</script>
