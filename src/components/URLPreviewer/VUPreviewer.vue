<template>
  <div v-if="githubDetails != {}" class="bg-gray-800 text-white rounded-lg">
    <div>
      <div>
        <img alt="" draggable="true" :src="githubDetails.Values" />
      </div>
    </div>
    <div class="p-3 w-full">
      <div>
        <p class="text-lg font-bold">
          {{ githubDetails.Title }}
        </p>
        <p class="text-xs font-extralight">
          {{ githubDetails.Descriptions }}
        </p>
      </div>
    </div>
  </div>
  <div class="" v-else></div>
</template>

<script>
import { parseURL } from "./parseURL";
import "../../tailwind.css";
export default {
  name: "VPreviewer",
  props: ["url"],
  data() {
    return {
      data: null,
      githubDetails: {},
    };
  },
  async mounted() {
    this.data = await parseURL(
      "https://url-parser-com.onrender.com/?url=" + this.url
    );
    if (this.data != null) {
      this.githubDetails = JSON.parse(JSON.stringify(this.data));
      console.log(this.data);
    }
  },
};
</script>
