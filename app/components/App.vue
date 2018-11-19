<template>
    <Page>
        <ActionBar title="Welcome to NativeScript-Vue!"/>
        <GridLayout columns="*" rows="*, auto">
            <Label class="fa" :text="'fa-cut' | fonticon" />
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

.message {
  vertical-align: center;
  text-align: center;
  font-size: 20;
  color: #333333;
}

.far {
    font-family: fa-regular-400;
    font-weight: 400;
  }
  
  .fab {
    font-family: fa-brands-400;
    font-weight: 400;
  }
  
  .fas {
    font-family: fa-solid-900;
    font-weight: 900;
  }
</style>
