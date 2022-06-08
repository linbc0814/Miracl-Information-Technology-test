<template>
  <div class="relative w-full h-full">
    <div class="bg-white">
    <section class="topItem">
      <div class="flex border-b-2 border-black">
        <div class="m-6">YOUTUBE</div>
        <div class="flex-grow"></div>
        <div class="my-6 ">Search</div>
        <div class="my-6 mx-4">user</div>
      </div>
    </section>
    <section class="headerItem">
      <div class="border-b-2 flex justify-start lg:justify-center overflow-x-auto ">
        <HeaderBtn />
        <HeaderBtn />
        <HeaderBtn />
        <HeaderBtn />
        <HeaderBtn />
        <HeaderBtn />
        <HeaderBtn />
        <HeaderBtn />
      </div>
    </section>
    </div>
    <section class="contentItem">
      <div class="flex gap-6 flex-wrap w-full justify-center mb-20">
        <ContentItem />
        <ContentItem />
        <ContentItem />
        <ContentItem />
        <ContentItem />
        <ContentItem />
        <ContentItem />
        <ContentItem />
        <ContentItem />
        <ContentItem />
        <ContentItem />
        <ContentItem />
      </div>
    </section>
    <section class="footerItem">
      <div class="flex justify-evenly  fixed inset-x-0 bottom-0 bg-white h-20 border-t border-black">
        <button>BTN1</button>
        <button>BTN2</button>
        <button>BTN3</button>
        <button>BTN4</button>
      </div>
    </section>
  </div>
</template>

<script>
import HeaderBtn from './components/headerBtn.vue'
import ContentItem from './components/contentItem.vue'

export default {
  name: 'App',
  components: { HeaderBtn, ContentItem }
}
</script>

<style lang="scss">
@import "./style/style.scss";
</style>
