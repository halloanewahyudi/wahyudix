<template>
    <div class="py-32">
       <Title title="Project" /> 
       <div class="max-w-6xl mx-auto">
           <div class="grid px-10  grid-cols-1 lg:grid-cols-2  gap-10">
               <div class="w-full ">
               <Thumbnail title="Sanur Elok Residence" description="Located in the triangle of CBD South Jakarta, SanurElok Residence offers luxury accommodation for both business and leisure travellers." link="http://sanurelokresidence.co.id/" target="_blank"/>
               </div>
               <div class="w-full ">
               <Thumbnail image="/images/project/kt/kt-cover.jpg" title="Kandang Ternak" description="Kandang Ternak Merupakan aplikasi anak bangsa yang memudahkan para konsumen dalam memenuhi kebutuhan sehari-hari atau event-event tertentu." link="https://kandangternak.id/" target="_blank" />
               </div>
               <div class="w-full">
               <Thumbnail  image="/images/project/wbs/wbs-cover.jpg" title="Widya Bhakti Sasana" description="architectural planning and contractor service company that was founded in 2019" link="https://widyabhaktisasana.com/" target="_blank"  />
               </div>
               <div class="w-full">
               <Thumbnail image="/images/project/apl/apl-cover.jpg" title="Adi Prasana Lestari" description="is one of the major companies engaged in the support of heavy equipment, especially in the fields of oil and gas, lifting equipment, construction equipment, and mining" link="http://adipradanalestari.co.id/" target="_blank" />
               </div>
                <div class="w-full">
               <Thumbnail image="/images/project/global/global-cover.jpg" title="Global HPL" description="supporting Indonesia’s interior designers for more than a decade with our laminate collections" link="https://globalhpl.com/" target="_blank" />
               </div>
                <div class="w-full">
               <Thumbnail image="/images/project/stc/stc-cover.jpg" title="Star Chrome Tools" description="Starchrome develops heavy duty tools that enhance professional users to perform critical tasks with confidence." link="https://www.starchrometools.com/" target="_blank" />
               </div>
           </div>
       </div>
    </div>
</template>
<script>
export default {
    name: 'ProjectPage',
    layout:'default'
  
}
</script>