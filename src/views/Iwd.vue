<template>
  <v-content class="pa-0">
    <v-container fluid class="mt-2 mb-0">
      <v-layout wrap align-center justify-center row fill-height class="my-0">
        <v-flex xs12 md5 class="mb-0">
          <span>GOOGLE DEVELOPERS</span>
          <h1
            class="google-font mb-0 mt-0"
            style="font-size: 200%; color: #000000"
          >
            Women Techmakers International Women's Day India Summit, 2023
          </h1>
          <p style="font-size: 120%">
            International Women's Day Conference by Women Techmakers is back
            again this year after a brief pause owing to the pandemic. This year
            we look forward to welcome around 500 Women in Tech and Allies at
            our conference. The same will have Tech Talks, Panel Discussions and
            Fireside Chats followed by Networking Sessions.
          </p>
          <p style="font-size: 120%">
            The theme for this year is DARE TO BE, empowering our community to
            have courage, to dream big and to be bold. #WTMDareToBe
          </p>
          <p style="font-size: 120%">
            Come join us on the 23rd of April, 2023 in Pune.
          </p>
          <p
            class="google-font mt-4 mb-2"
            style="font-size: 115%; color: #1a73e8; font-weight: 200"
          >
          <i class="fa fa-calendar"></i> &nbsp;23rd April |
            9:00 AM to 5:00 PM
          </p>
          <a style="text-decoration: none;" href="https://goo.gl/maps/o9M6WGyrvew5CjJ96">
          <p
          class="google-font mt-2 mb-2"
          style="font-size: 115%; color: #1a73e8; font-weight: 200"
        >
          <i class="fa fa-map-marker"></i> &nbsp; 
              Symbiosis Auditorium, Viman Nagar, Pune
        </p>
      </a>
          <p class="google-font mb-8" style="font-size: 110%; color: #9e9e9e">
            <span v-for="(item, i) in iwdHashTags" :key="i"
              >#{{ item }} &nbsp;</span
            >
          </p>
        </v-flex>
        <v-flex xs12 md5 class="mb-0" align-center justify-center style="text-align:center">
          <video id="bgVideo" preload="true" autoplay loop muted style="height:auto; width:70%;">
            <source src="../assets/gifs/iwd.mp4" type="video/mp4" /> 
         </video>
         </v-flex>
        <v-flex xs12 md10 class="">
          <v-btn
            href="https://bit.ly/iwdpune23"
            target="_blank"
            class="ma-0 google-font elevation-1"
            color="#1a73e8"
            style="text-transform: capitalize; border-radius: 5px; color: white"
            >Register Now</v-btn
          >
          &nbsp;

          <v-btn
            target="_blank"
            outline
            color="cyan"
            style="text-transform: capitalize; border-radius: 5px"
            class="ml-0"
            dark
            >Call For Speakers</v-btn
          >
        </v-flex>
      </v-layout>
    </v-container>
    <!-- <v-container fluid class="grey lighten-4 py-5">
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class>
          <stats />
        </v-flex>
      </v-layout>
    </v-container> -->
    <v-container fluid class="mt-1 mb-0">
      <v-layout wrap align-start row justify-center fill-height class="my-0">
        <v-flex xs12 md10 class="">
          <!-- <img src="../assets/img/schedule.jpeg" width="60%" height="60%" class="margin-auto"/> -->
          <h1
            class="google-font mb-0 mt-0 mb-4"
            style="font-size: 200%;"
          >
            Schedule
          </h1>
        <v-container fluid style="border-color:#black;border-width: 1px;border-style: solid;border-radius:20px">
          <v-layout wrap align-center justify-center row fill-height class="my-0">
              <v-flex xs6 md5 class="mb-0" align-center justify-center style="text-align:center">
                <p class="font-schedule">Registration</p>
                <p class="font-schedule">9:00 am - 10:00 am</p>
               </v-flex>
               <v-flex xs6 md5 class="mb-0" align-center justify-center style="text-align:center">
                <p class="font-schedule">Welcome Note</p>
                <p class="font-schedule">10:00 am - 10:15 am</p>
               </v-flex>
          </v-layout>
          <v-layout  wrap align-center justify-center  row fill-height>
            <h2
            class="google-font mb-0 mt-0"
            style="font-size: 170%;"
           
          >
            Agenda
          </h2>
        </v-layout>
        <hr class="my-3"/>
        <v-layout  wrap align-center justify-center  row fill-height>
        <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
          <p class="font-schedule">10:15 am - 10:45 am</p>
         </v-flex>
         <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
          <p class="font-schedule">DareToBe!</p>
         </v-flex>
         <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
          <!-- Speaker -->
         </v-flex>
         </v-layout>
         <v-layout  wrap align-center justify-center  row fill-height>
          <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
            <p class="font-schedule">10:45 am - 11:15 am</p>
           </v-flex>
           <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
            <p class="font-schedule">Transitioning from a Developer to a Technical Leader</p>
           </v-flex>
           <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
            <!-- Speaker -->
           </v-flex>
           </v-layout>
           <v-layout  wrap align-center justify-center  row fill-height>
            <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
              <p class="font-schedule">11:15 am - 11:45 am</p>
             </v-flex>
             <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
              <p class="font-schedule">Where there is a Will there is a Way!</p>
             </v-flex>
             <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
              <!-- Speaker -->
             </v-flex>
             </v-layout>
             <v-layout  wrap align-center justify-center  row fill-height>
              <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                <p class="font-schedule">11:45 am - 12:15 pm</p>
               </v-flex>
               <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                <p class="font-schedule">Let's flow with Dataflow</p>
               </v-flex>
               <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                <!-- Speaker -->
               </v-flex>
               </v-layout>
               <hr class="mt-2 mb-4"/>
               <v-layout  wrap align-center justify-center  row fill-height>
                <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                  <p class="font-schedule">12:15 pm - 01:00 pm</p>
                 </v-flex>
                 <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                  <p class="font-schedule">Activity</p>
                 </v-flex>
                 <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                  <!-- Speaker -->
                 </v-flex>
                 </v-layout>
                 <hr class="mt-2 mb-4"/>
               <v-layout  wrap align-center justify-center  row fill-height>
                <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                  <p class="font-schedule">01:00 pm - 02:00 pm</p>
                 </v-flex>
                 <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                  <p class="font-schedule">Lunch</p>
                 </v-flex>
                 <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                  <!-- Speaker -->
                 </v-flex>
                 </v-layout>
                 <hr class="mt-2 mb-4"/>
                 <v-layout  wrap align-center justify-center  row fill-height>
                  <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                    <p class="font-schedule">02:00 pm - 02:30 pm</p>
                   </v-flex>
                   <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                    <p class="font-schedule">Data Governance skills for Digital India</p>
                   </v-flex>
                   <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                    <!-- Speaker -->
                   </v-flex>
                   </v-layout>
                   <v-layout  wrap align-center justify-center  row fill-height>
                    <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                      <p class="font-schedule">02:30 pm - 03:00 pm</p>
                     </v-flex>
                     <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                      <p class="font-schedule">Big Data in the Financial Industry</p>
                     </v-flex>
                     <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                      <!-- Speaker -->
                     </v-flex>
                     </v-layout>
                     <v-layout  wrap align-center justify-center  row fill-height>
                      <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                        <p class="font-schedule">03:00 pm - 03:30 pm</p>
                       </v-flex>
                       <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                        <p class="font-schedule">Robotex india</p>
                       </v-flex>
                       <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                        <!-- Speaker -->
                       </v-flex>
                       </v-layout>
                       <hr class="mt-2 mb-4"/>
                       <v-layout  wrap align-center justify-center  row fill-height>
                        <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                          <p class="font-schedule">03:30 pm - 03:45 pm</p>
                         </v-flex>
                         <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                          <p class="font-schedule">Hi Tea & Snacks</p>
                         </v-flex>
                         <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                          <!-- Speaker -->
                         </v-flex>
                         </v-layout>
                         <hr class="mt-2 mb-4"/>
                         <v-layout  wrap align-center justify-center  row fill-height>
                          <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                            <p class="font-schedule">03:45 pm - 04:45 pm</p>
                           </v-flex>
                           <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                            <p class="font-schedule">Dare To Lead : A panel discussion with women in leadership</p>
                           </v-flex>
                           <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                            <!-- Speaker -->
                           </v-flex>
                           </v-layout>
                           <hr class="mt-2 mb-4"/>
                           <v-layout  wrap align-center justify-center  row fill-height>
                            <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                              <p class="font-schedule">04:45 pm - 05:00 pm</p>
                             </v-flex>
                             <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                              <p class="font-schedule">Thanking Note</p>
                             </v-flex>
                             <v-flex xs3 md3 class="mb-0" align-center justify-center style="text-align:center">
                              <!-- Speaker -->
                             </v-flex>
                             </v-layout>
                            </v-container>
        </v-flex>
      </v-layout>
    </v-container>
  </v-content>
</template>

<script>
import ChapterDetails from "@/assets/data/chapterDetails.json";

export default {
  components: {
    // stats: () => import("@/components/iwd/stats"),
  },
  data() {
    return {
      iwdHashTags: ChapterDetails.IWDHashTags,
    };
  },
};
</script>
