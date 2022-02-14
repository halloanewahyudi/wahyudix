<template>
  <div>
    <div class="w-full px-12 lg:w-10/12 mx-auto pt-40">
      <div class="flex flex-col lg:flex-row gap-4">
        <div class="w-full lg:w-4/12 p-4 flex flex-col items-end">
          <div class="w-52 relative mx-auto lg:mx-0">
            <Photo />
          </div>
        </div>
        <div class="w-full lg:w-8/12 bg-zinc-200 p-4">
          <div class="text-info italic">Sekilas</div>
          <h3 class="text-5xl font-bold text-serif text-info mb-5">
            Tentang Saya
          </h3>
          <p class="text-3xl">
            Lebih dari 5 tahun berkarya, beberapa perusahaan pernah bekerja sama
          </p>
          <p class="text-xl">
            Dimulai dari desain hingga bisa live tampil sebuah website adalah
            sebuah proses yang saya kerjakan website yang saya buat lebih
            dominan berbasis WordPress Saya memulai mengeluti di web developer
            kisaran tahun 2012 dan waktu itu masih cupu mungkin belum bisa
            profesional. membuat website cuma pakai html table dan photoshop.
          </p>
          <p class="text-xl">
            Diawali dengan perusahaan tempat saya bekerja banting setir dari
            usaha kontraktor sipil beralih ke pengambangan aplikasai blackberry,
            karena saya suka desain dan bisa menggunakan beberapa program desain
            maka saya yang tersisa dari tim kontraktor yang saat itu di
            rumahkan, dan saya di tugaskan mendesain UI untuk keperluan apps.
          </p>
          <p class="text-xl">
            Mulai dari sini saya mendapatkan lingkungan dan pengalaman baru,
            berbaur dengan tim sehingga keterlibatan saya dengan projek yang
            saling sinergi mendapatkan tambahan ilmu dan wawasan baru. Keinginan
            bisa membuat website membuat saya ingin belajar hal tersebut dan
            saya pelajari secara otodidak. Mulai saya pelajari
            HTML/CSS,jQuery,PHP hingga flatform cms dan fremework, WordPress,
            Codeigniter, Bootstrap
          </p>
        </div>
      </div>
    </div>
  <!--   Skill pengalaman -->
    <div class="max-w-6xl mx-auto px-10 pb-20">
      <div class="flex flex-col lg:flex-row gap-10">
        <div class="w-full lg:w-4/12">
          <TitleStrip title="Skill" class="mb-4" />
          <title-list
            title="Desain"
            description="Figma, Photoshop, Ai, Gimp, inkscape"
          ></title-list>
          <title-list
            title="Develove"
            description="HTML, CSS, PHP, Jquery, Javascript"
          ></title-list>
          <title-list
            title="Flatform/framework."
            description="Wordpress, Codeigniter,Nuxt, Bootstrap, Tailwind"
          ></title-list>
        </div>
        <div class="w-full lg:w-8/12">
          <TitleStrip title="Pengalaman" class="mb-4" />
          <div class="flex flex-col lg:flex-row gap-10">
            <div class="lg:w-6/12">
              <title-list
                title="UI desainer"
                description="7langit, 2009-2010"
              ></title-list>
              <title-list
                title="Web Support."
                description="i2-Integration, 2010-2013"
              ></title-list>
              <title-list
                title="Web Developer."
                description="Desain Bagus, 2013-2014"
              ></title-list>
            </div>
            <div class="lg:w-6/12">
              <title-list
                title="Web Developer."
                description="Proweb Indonesia, 2014-2018"
              ></title-list>
                <title-list
                title="Freelancer."
                description="Web developer , 2018- sekarang"
              ></title-list>
              </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>