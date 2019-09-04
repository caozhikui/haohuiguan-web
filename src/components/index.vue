<style scoped>
  .top{
    width: auto;
    height: 2.5vw;
    box-shadow: #f1f1f1 -1px 4px 3px 0px;
    line-height: 2.5vw;
  }
  .search{
    width: 20vw;
    height: 2.5vw;
    margin:0 auto;
    text-align: center;
    line-height:2.5vw;
  }
  .search input{
    height: 1.8vw;
    width: 15vw;
    border-radius:18px;
    background: #f7f7f7;
    border: 0px;
    text-align: center;
    outline: none;
  }
  .logo{
    width: 2vw;
    height: 2.5vw;
    float: left;
    margin-left: 5%;
  }
  .menu-div{
    width: 15vw;
    text-align: center;
  }
  .img-Menu{
    width: 30%;
    clear: none;
    display: inline-block;
    margin:0 auto;
  }

</style>
<template>
  <div class="top">
    <div class="logo">
      <Dropdown placement="bottom-start" >
            <a href="javascript:void(0)" style="display: block;width: 2vw;height: 2.5vw;text-align: center">
              <img src="../assets/gallery-view.png" style="vertical-align: middle; " height="20" width="20"/>
            </a>
        <Dropdown-menu slot="list" class="menu-div" >
          <Dropdown-item class="img-Menu" ><img src="../assets/logo.png" height="50" width="50"/></Dropdown-item>
          <Dropdown-item class="img-Menu" ><img src="../assets/logo.png" height="50" width="50"/></Dropdown-item>
          <Dropdown-item class="img-Menu" ><img src="../assets/logo.png" height="50" width="50"/></Dropdown-item>
          <Dropdown-item class="img-Menu" ><img src="../assets/logo.png" height="50" width="50"/></Dropdown-item>
          <Dropdown-item class="img-Menu" ><img src="../assets/logo.png" height="50" width="50"/></Dropdown-item>
        </Dropdown-menu>
      </Dropdown>
      <!--<img src="../assets/logo.png" height="20" width="100"/>-->
      </div>
    <div class="search">
      <input  type="text" placeholder="这里输入文字"  size="22"/>
    </div>
  </div>
</template>
<script>
export default {

}
</script>
