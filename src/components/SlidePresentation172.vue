<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">
      Event Queue comme exemple - FIFO (First in first out)
    </div>
    <div class="content">
      <MonacoEditor
        code='function Event(name, xCoordinate, yCoordinate){
    this.name = name;
    this.xCoordinate = xCoordinate;
    this.yCoordinate = yCoordinate;
}
const clickEvent = new Event("click", 213, 301);
const keypressEvent = new Event("keypress", 500, 612);
const mousemoveEvent = new Event("mousemove", 402, 102);

const events = [];
addEvent(clickEvent);
addEvent(keypressEvent);
addEvent(mousemoveEvent);

while(events.length !== 0){
    const event = events.pop();
    console.log("Event: " + event.name + " ex&eacute;cut&eacute; sur les coordonn&eacute;es "+ event.xCoordinate 
    + ", "+ event.yCoordinate);
}
console.log(events);

function addEvent(event){
    events.unshift(event);
}'
        editorIndex="47"
      />
    </div>
  </div>
</template>
