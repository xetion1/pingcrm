<template>



<div>
    <div >
        <Headers></Headers>
    </div>

    <div >
        <TeamAbout></TeamAbout>
    </div>

    <div>
        <Footer></Footer>
    </div>

</div>

</template>

<script>
import Headers from '@/Shared/Headers'
import Footer from '@/Shared/Footer'
import TeamAbout from '@/Shared/TeamAbout'

export default {
  metaInfo: { title: 'Team' },
  components: {
    Headers,
    TeamAbout,
    Footer,
  },
}
</script>
