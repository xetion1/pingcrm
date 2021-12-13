<template>



<div>
    <div >
        <Headers></Headers>
    </div>

    <div>
        <Video></Video>
    </div>

    <div>
        <Price></Price>
    </div>

    <div>
        <Quote></Quote>
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
import Price from '@/Shared/Price'
import Layout from '@/Shared/Layout'
import Video from '@/Shared/Video'
import Headers from '@/Shared/Headers'
import Quote from '@/Shared/Quote'
import Blog from '@/Shared/Blog'
import Footer from '@/Shared/Footer'

export default {
  metaInfo: { title: 'Dash' },
  components: {
    Video,
    Price,
    Headers,
    Quote,
    Blog,
    Footer,
  },
  //layout: Layout,
}
</script>
