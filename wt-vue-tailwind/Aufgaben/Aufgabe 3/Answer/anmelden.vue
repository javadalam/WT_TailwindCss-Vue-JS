<script setup>

</script>

<template>
   
      <div class=" flex-1 pt-8 bg-gray-200 text-gray-600">
         <div class="login-main">
           <div class="login-main-form">
             <div class="font-extrabold px-20 text-xl">Create Your Account</div>
               <form class="form" action="#" method="POST">
                 <div>
                    <label for="Email" class="form-lable"> Email Address </label>

                    <div class="mt-2">
                       <input
                        id="email"
                        name="email"
                       type="email"
                        autocomplete="email"
                        required
                        class="form-input"
                       />
                    </div>
                </div>
              <div>
                <lable for="password" class="form-lable"> Password </lable>

                <div class="mt-2">
                  <input
                    id="password"
                    name="password"
                    type="password"
                    autocomplete="current-password"
                    required
                    class="form-input"
                  />
                </div>
              </div>

              <div class="flex items-center px-8">
                          <input
                              id="terms-and-privacy"
                              name="terms-and-privacy"
                              type="checkbox"
                              class="rounded"
                          />
                          <label
                             for="terms-and-privacy"
                             class="ml-2 block text-sm text-gray-900"
                             >I agree to the
                             <a href="#" class="text-indigo-600 hover:text-indigo-500"
                             >Terms</a>
                           
                             and
                          <a href="#" class="text-indigo-600 hover:text-indigo-500"
                           >Privacy Policy</a>
                  
                          </label>
              </div>
            </form>
          </div>
        </div>
      </div>

</template>

