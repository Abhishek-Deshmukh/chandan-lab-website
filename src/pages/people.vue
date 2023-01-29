<template>
  <img src="/img/all.jpeg" class="pt-7">
  <div class="container mx-auto text-left">
    <h1 class="text-4xl underline pt-7 pl-3">
      People
    </h1>
    <h2 class="text-3xl pt-7 pl-8">
      Principal Investigator
    </h2>
    <!-- <div class="grid xl:grid-cols-2 md:grid-cols-2 sm:grid-cols-1 p-10">
      <div class="col-span-1">
        <img src="https://www.niser.ac.in/~chandan/images/content/demo-only/cglabnew.png">
      </div>
      <div class="col-span-2">
        <p class="text-2xl uppercase mb-3 mt-6">
          Dr.Chandan Goswami
        </p>

        <p class="text-3xl">
          <a class="icon-btn " href="mailto:chandan@niser.ac.in">
            <ant-design:mail-outlined class="mr-4" />
          </a>

          <a class="icon-btn" href="#">
            <akar-icons:facebook-fill class="mr-4" />
          </a>

          <a class="icon-btn" href="#">
            <akar-icons:twitter-fill class="mr-4" />
          </a>
        </p>
      </div>
    </div> -->

    <div class="grid xl:grid-cols-4 md:grid-cols-2 sm:grid-cols-1">
      <Card
        img="https://www.niser.ac.in/~chandan/images/content/demo-only/cglabnew.png"
        name="Dr. Chandan Goswami"
        description="Dr. Chandan Goswami did his PhD in 2006 from Freie Universität Berlin, Germany. He is currently working on Crosstalk between cytoskeleton and TRP channels, pain biology."
        position="Principal Investigator, Associate Professor, DAAD Research Ambasador, India."
      />
    </div>
    <h2 class="text-3xl pt-14 pl-8">
      Post-Doc Students
    </h2>
    <div class="grid xl:grid-cols-4 md:grid-cols-2 sm:grid-cols-1">
      <Card
        img="./img/satish.jpeg"
        name="Dr. Satish Kumar"
        description="Working on TRPV4 in mitochondria and Bone cells."
        position="Post Doc. Student"
      />
    </div>

    <h2 class="text-3xl pt-14 pl-8">
      Ph.D Students
    </h2>
    <div class="grid xl:grid-cols-4 md:grid-cols-2 sm:grid-cols-1">
      <Card
        img="./img/barsha.jpeg"
        name="Barsha Tripathy"
        description=""
        position="Graduate Student"
      />
      <Card
        img="./img/tusar.jpeg"
        name="Tusar Kanta Acharya"
        description="Working on TRPV4 in Mitocondria. "
        position="Graduate Student"
      />

      <Card
        img="./img/FB_IMG_1638814939089 - Ram Prasad Sahu.jpg"
        name="Ram Prasad Sahu"
        description="Working on TRPV3 channel and interested in reading, music and playing musical instruments."
        position="Graduate Student"
      />

      <Card
        img="./img/IMG_20220124_130500_Bokeh - Nishant Kumar Dubey.jpg"
        name="Nishant Kumar Dubey"
        description="Working on TRPV4 and catsper channels."
        position="Graduate Student"
      />

      <Card
        img="./img/IMG-20211031-WA0008 - Sushama Mohanta.jpg"
        name="Sushama Mohanta"
        description="Working on TRPV1."
        position="Graduate Student"
      />

      <Card
        img="./img/Screenshot_20220124-091616_Photos - Deep Shikha.jpg"
        name="Deep Shikha"
        description="Working on TRPA1,TRPM8 and glia cells ."
        position="Graduate Student"
      />

      <Card
        img="./img/Parnshree.jpg"
        name="Parnasree Mahapatra"
        description="Working on TRPV3/V4/M8."
        position="Graduate Student"
      />
    </div>

    <h2 class="text-3xl pt-7 pl-8">
      Master's Students
    </h2>
    <div class="grid xl:grid-cols-4 md:grid-cols-2 sm:grid-cols-1">
      <Card
        img="./img/subham.jpeg"
        name="Subham Mishra"
        description="Working on TRPV4 in bone cells."
        position="Master's Student (2019-24)"
      />
      <Card
        img="./img/nilesh.jpeg"
        name="Nilesh Kumar Das"
        description="Working on TRPV4,TRPV3 and neurons."
        position="Master's Student (2019-24)"
      />
      <Card
        img="./img/raima.jpeg"
        name="Raima Singh"
        description="Working on TRPM8 and TRPA1."
        position="Master's Student (2019-24)"
      />
      <Card
        img="./img/IMG_20220116_151557_308 - Shamit Kumar.jpg"
        name="Shamit Kumar"
        description="He working om TRPM7,TRPM8, TRPV4 and adipoocytes."
        position="Master's Student (2018-23)"
      />

      <Card
        img="./img/tejas.jpeg"
        name="Tejas Pravin Rokade"
        description="He is working on TRPV3,TRPV4 in Lysosome."
        position="Master's Student (2018-23)"
      />

      <Card
        img="./img/shreya.jpeg"
        name="Shreya Soni"
        description="Working on TRPV4 and aquaporins in Fish cells."
        position="Master's Student (2018-23)"
      />

      <Card
        img="./img/harshit.jpeg"
        name="Harshit Haldua"
        description="Working on TRPM2."
        position="Master's Student (2018-23)"
      />

      <Card
        img="./img/ritesh.jpeg"
        name="Ritesh Dalai"
        description="Passionate about coding and simulating molecular interactions of protein channels and working on TRRV3 and TRPV4 channles."
        position="Master's Student (2017-22)"
      />
    </div>
    <h2 class="text-3xl pt-7 pl-8">
      Project Students
    </h2>
    <div class="grid xl:grid-cols-4 md:grid-cols-2 sm:grid-cols-1">
      <Card
        img="/img/Anushka.jpeg"
        name="Anushka Banerjee"
        description=""
        position="Project Student"
      />
      <Card
        img="/img/bidhu.jpeg"
        name="Bibhudutta Sahoo"
        description=""
        position="Project Student"
      />
      <Card
        img="./img/shweta.jpeg"
        name="Shweta"
        description="PhD student from KIIT institute"
        position="Project Student"
      />
      <Card
        img="./img/Ranabir - Ranabir Chakraborty.jpg"
        name="Ranabir Chakraborty"
        description="PhD student at Institut Pasteur, Paris France in 2022."
      />
    </div>
    <h2 class="text-3xl pt-7 pl-8">
      Alumni
    </h2>
    <div class="grid xl:grid-cols-4 md:grid-cols-2 sm:grid-cols-1">
      <Card
        img="./img/ashutosh.jpeg"
        name="Dr. Ashutosh Kumar (2010-2016)"
        description="Current Position: Senior post-doctoral fellow in Washinton University, School of Medicine, USA. "
      />
      <Card
        img="./img/pushpendu.jpeg"
        name="Dr. Pushpendu Sardar (2010-2012)"
        description="Current Position: Post doctorate fellow at the Department of Medicine, Cambridge University, UK in Sept 2021"
      />
      <Card
        img="./img/manoj.jpeg"
        name="Dr. Manoj Yadav (2012-2017)"
        description="Current Position: Post-doctoral fellow National Institute of Health (NIH), Bethesda, USA form 2019."
      />
      <Card
        img="./img/rakesh.jpeg"
        name="Dr. Rakesh Kumar Majhi (2012-2017)"
        description="Current Position: IIT Kanpur as Assistant Professor from 2022."
      />
      <Card
        img="./img/shikha.jpeg"
        name="Dr. Shikha Kumari (2012-2014)"
        description="Current Position:Post-doctoral fellow in Wellcome Center for Integrative Parasitology at the University of Glasgow, June 2020 "
      />
      <Card
        img="./img/arjith.jpeg"
        name="Arijit Ghosh (2012-2016)"
        description="Post-doctoral fellow in National heart , lungs and blood institute, USA"
        position="Master's Student"
      />
      <Card
        img="./img/anurag.jpeg"
        name="Dr. Anurag Priyadarshi (2013-2015)"
        description="Current Position: National Institute of Health, USA as a post doctorate fellow "
      />
      <Card
        img="./img/somadatta.jpeg"
        name="Dr. Somdatta Saha (2014-2020)"
        description="Current Position: Post-doctoral fellow in Virginia Commonwealth University, USA in 2021. "
      />
      <Card
        img="./img/rashmita.jpeg"
        name="Dr. Rashmita Das (2015-2022)"
        description="Current Position: pHD completed in 2022. "
      />
      <Card
        img="./img/nikhil.jpeg"
        name="Dr. Nikhil Tiwari (2016-208)"
        description="Current Position: Joined Leibniz-Institut für Neurobiologie (LIN), Magdeburg, Germany as a PhD student. Oct 2018) "
      />
      <Card
        img="./img/aiswrya.jpeg"
        name=" Aiswarya Shivanand (2016-2018)"
        description=" JRF at Indian Institute of Science since 2019"
        position="Master's Student"
      />
      <Card
        img="./img/tanaya.jpeg"
        name=" Tanaya Saha (2016-2018)"
        description=" Joined as a JRF at NII, New Delhi 2018."
        position="Master's Student"
      />
      <Card
        img="./img/divyanshi.jpeg"
        name="Divyanshi (2017-2019)"
        description="Joined University of Illinois at Urbana-Champaign as a PhD student. Oct 2018."
        position="Master's Student"
      />
      <Card
        img="./img/stuti.jpg"
        name="Stuti Gupta (2017-2019)"
        description="Joined University of Iowa, USA as a PhD student. 2019"
        position="Master's Student"
      />
      <Card
        img="./img/subhadra.jpeg"
        name="Subhadra Majhi (2014-2019)"
        description="SPCB assistent environmental scientist"
        position="Master's Student"
      />
      <Card
        img="./img/Samiksya.jpg"
        name="Samikshya Sucharita (2017-2019)"
        description=""
        position="Master's Student"
      />
      <Card
        img="./img/priyadharshan.jpeg"
        name="Priyadarshan Pradhan (2018-2020)"
        description=" Joined as a Lecturer in SCVB collage Palampur, Himachal"
        position="Master's Student"
      />
      <Card
        img="./img/srujanika.jpeg"
        name="Srujanika (2016-2021) "
        description="PhD student in instem, Bangalore in 2022."
        position="Master's Student"
      />
      <Card
        img="./img/aniket modak.jpeg"
        name="Aniket Modak (2017-2022)"
        description="MBA student in IIM, Ahmedabad in 2022."
        position="Master's Student"
      />
      <Card
        img="./img/IMG_20190509_084727 - Anushka Jain.jpg"
        name="Anushka Jain (2017-2022)"
        description="PhD student in University of Rochester, USA in 2022."
        position="Master's Student"
      />
    </div>
  </div>
  <router-link to="/gallery">
    <div class="windi-banner bg-blue-200 dark:bg-blue-900 pb-10 pt-10">
      <h1 class="text-4xl">
        Gallery
      </h1>
    </div>
  </router-link>
</template>
