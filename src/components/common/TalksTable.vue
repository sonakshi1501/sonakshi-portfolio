<template>
  <table class="table">
    <thead>
      <tr>
        <th scope="col">#</th>
        <th scope="col">Talk Tittle</th>
        <th scope="col">Date</th>
        <th scope="col">Community</th>
        <th scope="col">TechStack</th>
      </tr>
    </thead>
    <tbody>
      <tr v-for="(element, index) in talks" :key="index">
        <th scope="row">{{ index + 1 }}</th>
        <td>{{ element.talkTitle }}</td>
        <td>{{ element.date }}</td>
        <td>{{ element.communityName }}</td>
        <td>
          <span
            class="mychip2"
            v-for="(element, index) in element.techStack"
            :key="index"
          >
            {{ element }}
          </span>
        </td>
      </tr>
    </tbody>
  </table>
</template>

<script>
import talksData from "../../assets/data/talks.json";
export default {
  name: "AppTalksTable",
  data: () => ({
    talks: talksData,
  }),
};
</script>

<style>
.mychip2 {
  border: 1px solid black;
  margin-right: 8px;
  border-radius: 50px;
  padding-left: 12px;
  padding-right: 10px;
  text-align: center;
  padding-bottom: 5px;
  font-size: 70%;
}
</style>