<template>
    <Page>
        <ActionBar title="Welcome to NativeScript-Vue!"/>
        <GridLayout columns="*, *" rows="*, 4*, 4*, *">
            <Button class="fa" :text="'fa-map' | fonticon" row="1" col="0" />
            <Button class="fa" :text="'fa-map-pin' | fonticon" row="1" col="1" />
            <Button class="fa" :text="'fa-list' | fonticon" row="2" col="0" />
            <Button class="fa" :text="'fa-cog' | fonticon" row="2" col="1" />
        </GridLayout>
    </Page>
</template>

<script>
export default {
  data() {
    return {
      msg: "Hello World!"
    };
  }
};
</script>

<style scoped>
ActionBar {
  background-color: #53ba82;
  color: #ffffff;
}

Button {
    font-size: 50%;
    background: dodgerblue;
    color: white;
}
</style>
