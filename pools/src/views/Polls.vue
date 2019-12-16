<template>
  <div class="about">
    <div class="container">
      <div class="row" v-for="i in 5">
        <div class="col s12 m6">
          <ul class="collection with-header z-depth-2">
            <li class="collection-header blue darken-3 white-text">
              <p>First Names</p>
            </li>
            <li class="collection-item">
              <span class="new badge" data-badge-caption="vote">4</span>
              <label>
                <input class="with-gap" name="group1" type="radio" />
                <span>Green</span>
              </label>
            </li>
            <li class="collection-item">
              <label>
                <input class="with-gap" name="group1" type="radio" />
                <span>Green</span>
              </label>
            </li>
            <li class="collection-item">
              <label>
                <input class="with-gap" name="group1" type="radio" />
                <span>Green</span>
              </label>
            </li>
            <li class="collection-item">
              <label>
                <input class="with-gap" name="group1" type="radio" />
                <span>Green</span>
              </label>
            </li>

            <li class="collection-item footer">
              <div>
              <button type="submit" name="btn_login" class="col  s12 m6 push-m3 blue btn btn-small  white-text  waves-effect z-depth-1 y-depth-1" >Login</button>
              </div>
            </li>
          </ul>
        </div>
        <div class="col s12 m6">

        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "polls",
  data() {
    return {
        polls:''  
    }
  },
  methods: {
    getData(){}
  },
};
</script>

<style lang="scss" scoped>
.collection {
  li {
    p {
      padding: 0px;
      margin: 5px 0px;
    }
    label{
      display: block;
    }
  }
  .footer{
    padding: 15px 10px;
    background-color: #e1e1e1;
    &::after{
      display: block;
      clear: both;
      content:""
    }
  }
}

.about{
  background: #fbfbfb;
  padding: 50px 0px
}
</style>
