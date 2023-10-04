<template>
  <div>
  <sgds-footer :title="footerAttr.title" :description="footerAttr.description" :lastUpdatedDate="footerAttr.date" .:links="footerAttr.links"></sgds-footer>
  </div>
  </template>
  
  <script lang='ts'>
  import { computed } from "vue";
  
  export default {
    setup() {
      const footerAttr = computed(() => ({
        title: "Singapore Design System",
        description: "this is a description",
        date: new Date().toDateString(),
        links : [
          {
              "title": "Column 1",
              "links" : [
                  {
                      "href": "#1",
                      "label": "About Us"
                  },
                  {
                      "href": "#2",
                      "label": "This is a super long link"
                  },
                  {
                      "href": "#3",
                      "label": "Test"
                  },
                  {
                      "href": "#4",
                      "label": "Test"
                  }
              ]
          },
          {
              "title": "Column 2",
              "links" : [
                  {
                      "href": "#1",
                      "label": "About Us"
                  },
                  {
                      "href": "#2",
                      "label": "This is a super long link"
                  },
                  {
                      "href": "#3",
                      "label": "Test"
                  },
                  {
                      "href": "#4",
                      "label": "Test"
                  }
              ]
          },
          {
              "title": "Column 3",
              "links" : [
                  {
                      "href": "#1",
                      "label": "About Us"
                  },
                  {
                      "href": "#2",
                      "label": "This is a super long link"
                  },
                  {
                      "href": "#3",
                      "label": "Test"
                  },
                  {
                      "href": "#4",
                      "label": "Test"
                  }
              ]
          },
          {
              "title": "Column 4",
              "links" : [
                  {
                      "href": "#1",
                      "label": "About Us"
                  },
                  {
                      "href": "#2",
                      "label": "This is a super long link"
                  },
                  {
                      "href": "#3",
                      "label": "Test"
                  },
                  {
                      "href": "#4",
                      "label": "Test"
                  }
              ]
          },
          {
              "title": "Column 5",
              "links" : [
                  {
                      "href": "#1",
                      "label": "About Us"
                  },
                  {
                      "href": "#2",
                      "label": "This is a super long link"
                  },
                  {
                      "href": "#3",
                      "label": "Test"
                  },
                  {
                      "href": "#4",
                      "label": "Test"
                  }
              ]
          },
          {
              "title": "Column 6",
              "links" : [
                  {
                      "href": "#1",
                      "label": "About Us"
                  },
                  {
                      "href": "#2",
                      "label": "This is a super long link"
                  },
                  {
                      "href": "#3",
                      "label": "Test"
                  },
                  {
                      "href": "#4",
                      "label": "Test"
                  }
              ]
          }
        ]
      }))
      return { footerAttr };
    },
  };
  </script>
