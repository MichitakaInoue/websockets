<template>
  <div class="row">
    <div class="col-8">
      <div class="card card-default">
        <div class="card-header">
          Message
        </div>
        <div class="card-body p-0">
          <ul class="list-unstyled" style="height: 300px; overflow-y:scroll">
            <li class="p-2">
              <strong>michi</strong>
              messsage text
            </li>
          </ul>
        </div>
        <input type="text" name="message"  placeholder="Enter your message ..." class="form-controll" value="">
        <span class="text-muted">user is typing...</span>
      </div>
    </div>


    <div class="col-4">
      <div class="card card-default">
        <div class="card-header">
          Active Users
        </div>
        <div class="card-body">
          <ul>
            <li class="py-2">michi</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>



<script>
  export default{
    moutend(){
      console.log('Component moutend')
    }
  }
</script>
