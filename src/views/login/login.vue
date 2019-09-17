<template>

    <div id="main" class="main-warp">
        <div class="main-content">
            <div class="formDiv">
                
                    <h2 class="text-center">登录</h2>
                
                <form id="loginForm" method="post">
                    <div class="dataform">
                        <div class="input-warp gap">
                            <span class="input-icon iconfont icon-yonghu1"></span>
                            <input id="userName" name="username" type="text" class="inputs" placeholder="手机号码或邮箱" maxlength="64">
                        </div>
                        <div class="error-content">
                            <span id="userNameErr" class="errMsg"></span>
                        </div>

                        <div class="input-warp gap">
                            <span class="input-icon iconfont icon-baomi"></span>
                            <input class="inputs" type="password" name="password" placeholder="密码" id="pwd" maxlength="20">
                        </div>
                        <div class="error-content">
                            <span id="passwordErr" class="errMsg"></span>
                        </div>

                        <div class="btn-warp gap">
                            <div class="text-center">                               
                                <input type="hidden" value="jsform" id="_app">
                                <button type="submit" id="btnLogin" class="btn btn-block lgbtn blue">登录</button>
                            </div>
                        </div>
                        <div class="gap">
                            
                                <div class="pull-right" style="margin-top: 6px"><a href="javascript:;" class="link">忘记密码</a><span class="split-space">|</span><a href="register.html" class="link">新用户注册</a></div>
                            
                            <div class="pretty-box">
                                <input type="checkbox" value="1" name="REMEMBER" id="remember" class="">
                                <label for="remember" style="font-weight: normal">记住我</label>
                            </div>
                        </div>

                        
                            <div class="biggap third-party-title">
                                <h5 class="text-center"><span>第三方账号登录</span></h5>
                            </div>
                            <div class="third-auth">                              
                                
                                <a title="用钉钉登录" class="dt" href="javascript:;"></a>                                
                                <a title="用微信账户登录" class="wx" href="javascript:;"></a>
                                <a title="用QQ账户登录" class="qq" href="javascript:;"></a>
                                
                            </div>
                        
                    </div>
                </form>

            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped src= '@/styles/css/bootstrap.min.css'></style>
<style scoped src= '@/styles/css/login.css'></style>

