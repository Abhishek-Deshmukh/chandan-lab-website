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
        position="Principal Investigator"
      />
    </div>

    <h2 class="text-3xl pt-14 pl-8">
      Ph.D Students
    </h2>
    <div class="grid xl:grid-cols-4 md:grid-cols-2 sm:grid-cols-1">
      <Card
        img="./img/satish.jpeg"
        name="Dr. Satish Kumar"
        description=""
        position="Post Doc. Student"
      />

      <Card
        img="./img/tusar.jpeg"
        name="Tusar Kanta Acharya"
        description="Working on TRPV4 in Mitocondria."
        position="Graduate Student"
      />

      <Card
        img="./img/FB_IMG_1638814939089 - Ram Prasad Sahu.jpg"
        name="Ram Prasad Sahoo"
        description="Interested in reading ,music and playing musical instruments."
        position="Graduate Student"
      />

      <Card
        img="./img/IMG_20220124_130500_Bokeh - Nishant Kumar Dubey.jpg"
        name="Nishant Kumar Dubey"
        description="I am curious and want to learn new things and so is my taste in Research as well. I have spend some time in few different research fields like genomic analysis and Protein expression and functions."
        position="Graduate Student"
      />

      <Card
        img="./img/IMG-20211031-WA0008 - Sushama Mohanta.jpg"
        name="Sushama Mohanta"
        description="Currently Working on TRPV1."
        position="Graduate Student"
      />

      <Card
        img="./img/Screenshot_20220124-091616_Photos - Deep Shikha.jpg"
        name="Deep Shikha"
        description="PhD scholar at School of Biological Science, NISER."
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
        description=""
        position="Master's Student (2019-24)"
      />
      <Card
        img="./img/nilesh.jpeg"
        name="Nilesh Kumar Das"
        description=""
        position="Master's Student (2019-24)"
      />
      <Card
        img="./img/raima.jpeg"
        name="Raima Singh"
        description=""
        position="Master's Student (2019-24)"
      />
      <Card
        img="./img/IMG_20220116_151557_308 - Shamit Kumar.jpg"
        name="Shamit Kumar"
        description="I hail from New Delhi. Currently pursuing my Master's. Connecting the dots of mitochondria, adipocytes and TRP channels. After all these years, I can say 'Life is hard man'. "
        position="Master's Student (2018-23)"
      />

      <Card
        img="./img/tejas.jpeg"
        name="Tejas Pravin Rokade"
        description="Mumbai se aya tera dost. Working on Thermosensitive Ion channels TRPV3 and TRPV4."
        position="Master's Student (2018-23)"
      />

      <Card
        img="./img/shreya.jpeg"
        name="Shreya Soni"
        description="I'm born and brought up in Dhanbad, currently pursuing Masters in Life Sciences from NISER. I'm involved in the understanding of osmoregulation of TRPV4.
My hobbies include singing and watching web series. I'm a foodie and I prefer mountains over beaches."
        position="Master's Student (2018-23)"
      />

      <Card
        img="./img/harshit.jpeg"
        name="Harshit Haldua"
        description="Currently working on TRPM2."
        position="Master's Student (2018-23)"
      />

      <Card
        img="./img/ritesh.jpeg"
        name="Ritesh Dalai"
        description="Very passionate about coding and simulating molecular interactions of protein channels. Also am nerd/geek who enjoy strumming his guitar sometimes, programming and building packages, FPS and MMORPG gaming fanatic."
        position="Master's Student (2017-22)"
      />
    </div>
    <h2 class="text-3xl pt-7 pl-8">
      Alumni
    </h2>
    <div class="grid xl:grid-cols-4 md:grid-cols-2 sm:grid-cols-1">
      <Card
        img="./img/ashutosh.jpeg"
        name="Dr. Ashutosh Kumar (2010-2016)"
        description="Current Position: Joining as PDF in Washinton University, School of Medicinne, USA. "
      />
      <Card
        img="./img/manoj.jpeg"
        name="Dr. Manoj Yadav (2012-2017)"
        description="Current Position: Joining as a PDF in National Institute of Health (NIH), Bethesda, USA form 2019."
      />
      <Card
        img="./img/rakesh.jpeg"
        name="Dr. Rakesh Kumar Majhi (2012-2017)"
        description="Current Position: Joining in IIT Kanpur as Assistant Professor in 2022."
      />
      <Card
        img="./img/not-available.jpeg"
        name="Dr. Somdatta Saha (2014-2020)"
        description="Current Position: Joined as PDF in Virginia Commonwealth University, USA in 2021. "
      />
      <Card
        img="./img/rashmita.jpeg"
        name="Dr. Rashmita Das (2015-2022)"
        description="Current Position: Joined as PDF"
      />
      <Card
        img="./img/Ranabir - Ranabir Chakraborty.jpg"
        name="Ranabir Chakraborty"
        description="Joining as PhD student at Institut Pasteur, Paris France in 2022."
      />

      <Card
        img="./img/IMG_20190509_084727 - Anushka Jain.jpg"
        name="Anushka Jain"
        description="Joining as a PhD student in University of Rochester, USA in 2022."
      />
    </div>
  </div>
</template>
