<template>
    <h1>Home components</h1>
    <h1>{{text}}</h1>
    <div v-html="tag"></div>
    <div v-html="name"></div>
  </template>
  
  <script>


  export default {
    name: 'HomeComponent',
    data() {
        return {
            text: "Rahul Kumar Yadav",
            tag:"<h1>HTML Biding</h1>",
            name:"<h2>Divya</h2>"
        }
    }
  }
  </script>
  