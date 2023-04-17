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
          <h1
            class="google-font mb-0 mt-0 mb-4"
            style="font-size: 200%;"
          >
            Schedule
          </h1>
          <img src="../assets/img/schedule.jpeg" width="60%" height="60%" class="margin-auto"/>
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
