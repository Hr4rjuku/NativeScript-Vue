<template>
    <Page>
      <StackLayout>
        <Button text="testtest"/>
        <Label text="blabla"/>
        <temp test="TEST ME TEST ME!!">

        </temp>
      </StackLayout>
    </Page>

</template>

<script>
import temp from './templates/temp'
export default {
    components: {
      temp
    },
    data() {
        return {

        }
    }
}
</script>

<style scoped>

</style>