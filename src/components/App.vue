<template>
    <Page>
        <ActionBar title="Welcome to NativeScript-Vue!"/>
        <GridLayout columns="*" rows="*">
            <Label class="message" :text="msg" col="0" row="0"/>
            <Button text="HALLLO" @tap="$navigateTo(Home)"/>
        </GridLayout>
    </Page>
</template>

<script >
import Home from "./Home";
  export default {
    data() {
      return {
        Home: Home,
      }
    }
  }
</script>

<style scoped>

</style>
