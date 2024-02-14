<template>
  <h1>CSS Pseudo-Classes</h1>
  <p>A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s).</p>
  <div class="code">
    selector:pseudo-class { <br>
    &emsp;&emsp;property: value; <br>
    }
  </div>
  <HoverActiveExample/>
  <ChildExample/>
  <TypeExample/>
  <IsWhereExample/>
  <HasExample/>
  <FunctionalExamples/>
</template>

<style scoped>
.code{
  font: 1em Consolas, monospace;
  margin: auto;
  background-color: #eee;
  padding: 20px;
  width: 250px;
  text-align: left;
  border-radius: 10px;
}
</style>

<script setup>
import HoverActiveExample from "@/components/Examples/HoverActiveExample.vue";
import ChildExample from "@/components/Examples/ChildExample.vue";
import FunctionalExamples from "@/components/Examples/FunctionalExamples.vue";
import TypeExample from "@/components/Examples/TypeExample.vue";
import IsWhereExample from "@/components/Examples/IsWhereExample.vue";
import HasExample from "@/components/Examples/HasExample.vue";
</script>
