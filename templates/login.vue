<template>
    

        <div class="container">
            <div class="row" style="height: 100vh;">


                <div class="col-md-5" style="margin: auto; align-self: center  ;">
                    <div class="card shadow">

                        <div class="card-body">
                            <div class="text-center" style="padding: 3%;">
                                <img src="assets/img/MillerLogoFromMarketing.png" alt="Miller logo" width="50%">

                            </div>
                            <form style="padding: 5% ;" action="./landing.html" method="GET">
                                <div class="mb-3">
                                    <label for="exampleInputEmail1" class="form-label">Email address</label>
                                    <input type="email" class="form-control" id="exampleInputEmail1"
                                        aria-describedby="emailHelp">
                                    <!-- <div id="emailHelp" class="form-text">We'll never share your email with anyone else.
                                </div>-->
                                </div>
                                <div class="mb-3">
                                    <label for="exampleInputPassword1" class="form-label">Password</label>
                                    <input type="password" class="form-control" id="exampleInputPassword1">
                                </div>
                                <!--<div class="mb-3 form-check">
                                <input type="checkbox" class="form-check-input" id="exampleCheck1">
                                <label class="form-check-label" for="exampleCheck1">Check me out</label>
                            </div>-->
                                <button type="submit" class="btn mt-3"
                                    style="background-color: #007A4D; color: white; ">Submit</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>

</template>

<script>
export default {
  name: 'loginPage',
  props: {
  }
}
</script>
