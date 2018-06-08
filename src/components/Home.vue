<template>
  <Page class="page">
    <!-- <ActionBar class="action-bar" title="Home" backgroundColor="black"/> -->
    <StackLayout>
      <Image src="~/images/NativeScript-Vue.png"/>
    </StackLayout>
    <StackLayout class="bottom">
      <!-- <Button class="btn btn-primary" @tap="$router.push('/counter')">Counter</Button> -->
      <Button class="button-copy" @tap="$router.push('/hello')">登录</Button>
      <Button class="link">联系客服</Button>
    </StackLayout>

  </Page>
</template>

<script>

</script>
 
<style scoped>
  .bottom{
    margin-top: 70%;
  }
  .button-copy{
  color:black;
  background-color: goldenrod;
  border-radius: 20px;
  font-weight: bold;
  }
  .btn-primary{
    color:goldenrod;
  }
  .label-text{
    color:goldenrod;
  }
  /* From platform.ios.css */
.link {
    border-width: 0;
    color:goldenrod;
}
</style>

