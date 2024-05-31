<template>
  <div class="px-5">
    <v-row class="mt-0">
      <v-col cols="9">
        <v-row>
          <v-col cols="8" class="pa-2">
            <v-sheet
              style="background-color: #533737; height: 300px"
              class="text-format"
            >
              <h1>1 is a flys.</h1>
            </v-sheet>
          </v-col>
          <v-col cols="4" class="pa-2">
            <v-sheet
              style="background-color: #37533d; height: 300px"
              class="text-format"
            >
              <h1>2 is a fish.</h1>
            </v-sheet>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="8" class="pa-2">
            <v-sheet
              style="background-color: #3b3753; height: 200px"
              class="text-format"
            >
              <h1>3 is not a tree.</h1>
            </v-sheet>
          </v-col>
          <v-col cols="4" class="pa-2">
            <v-sheet
              style="background-color: #374f53; height: 200px"
              class="text-format"
            >
              <h1>4 will win three of a kind.</h1>
            </v-sheet>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12" class="pa-2">
            <v-sheet
              style="background-color: #535237; height: 300px"
              class="text-format"
            >
              <h1>Prepare your mop.</h1>
            </v-sheet>
          </v-col>
        </v-row>
      </v-col>

      <v-col cols="3" class="pa-2">
        <v-sheet
          style="background-color: #533751; height: 100%"
          class="text-format"
        >
          <h1>5 is a laughing.</h1>
        </v-sheet>
      </v-col>
    </v-row>
  </div>
</template>

<script>
import { defineComponent } from "vue";
// import axios from "axios";

// Components

export default defineComponent({
  name: "HomeView",
  // mounted() {
  //   this.getData();
  // },
  data() {
    return {
      // data_json: {},
    };
  },
  // methods: {
  //   ติดเรื่องของ CORS ไม่สามารถยิง API เข้าถึง  Backend ได้ครับ
  //   async getData() {
  //     let result = await axios.get(
  //       "https://demotrade.efintradeplus.com/ExamAPI/examdata"
  //     );
  //     this.data = result.data;
  //     console.log(result.data);
  //   },
  // },
});
</script>

<style scoped>
.text-format {
  color: white;
  font-size: 10px;
  font-weight: bolder;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
