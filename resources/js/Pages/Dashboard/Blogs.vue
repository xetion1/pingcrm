<template>



<div>
    <div >
        <Headers></Headers>
    </div>

    <div>
        <Contact></Contact>
    </div>


    <div>
        <Blog></Blog>
    </div>

    <div>
        <Footer></Footer>
    </div>

</div>

</template>

<script>
import Headers from '@/Shared/Headers'
import Footer from '@/Shared/Footer'
import Contact from '@/Shared/Blog/Contact'
import Blog from '@/Shared/Blog/Blog'

export default {
  metaInfo: { title: 'Blog' },
  components: {
    Headers,
    Contact,
    Blog,
    
    Footer,
  },
}
</script>
