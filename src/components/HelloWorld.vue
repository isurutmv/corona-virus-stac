<template>
  <div class="hello">
    <div class="container">
            <div class="section-title color-two text-center">
                <h2 class="title wow pixFadeUp" style="visibility: visible; animation-name: pixFadeUp;">
                    COVID-19 Situation Report
                </h2>
                <h4>{{date}}</h4>
                <p class="wow fadeInUp" data-wow-delay="0.3s" style="visibility: visible; animation-delay: 0.3s; animation-name: fadeInUp;">
                   
                </p>
            </div>
            <!-- /.section-title -->

             <h3 class="title wow pixFadeUp" style="visibility: visible; animation-name: pixFadeUp;">
                    Sri Lanka
                </h3>
                <br>
            <div class="countup-wrapper-two">
                <div class="row no-gutters pricing-amount change-subs-duration">
                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-four wow pixFadeUp" data-wow-delay="0.3s" style="visibility: visible; animation-delay: 0.3s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-ambulance"></i>
                            </div>
                            <div class="counter">
                                <p>New Cases</p>
                                <div class="local">
                                    <h4 class="count" data-counter="15">15</h4>
                                </div>
                                <div class="global">
                                    <h4 class="count">{{info.local_new_cases}}</h4>
                                </div>
                            </div>
                            <!-- /.counter -->
                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->

                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-two wow pixFadeUp" data-wow-delay="0.5s" style="visibility: visible; animation-delay: 0.5s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-hospital-alt"></i>
                            </div>
                            <div class="counter">
                                <p>Total Cases</p>
                                <div class="local">
                                    <h4 class="count" data-counter="43"></h4>
                                </div>
                                <div class="global">
                                    <h4 class="count">{{info.local_total_cases}}</h4>
                                </div>
                            </div>
                            <!-- /.counter -->

                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->

                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-three wow pixFadeUp" data-wow-delay="0.7s" style="visibility: visible; animation-delay: 0.7s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-bed"></i>
                            </div>
                            <div class="counter">
                                <p>Deaths</p>
                              
                                <div class="global">
                                    <h4 class="count">{{info.local_new_deaths}}</h4>
                                </div>
                            </div>
                            <!-- /.counter -->

                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->

                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-five wow pixFadeUp" data-wow-delay="0.9s" style="visibility: visible; animation-delay: 0.9s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-procedures"></i>
                            </div>
                            <div class="counter">
                                <p>Total Recovered</p>
                             
                                <div class="global">
                                    <h4 class="count">{{info.local_recovered}}</h4>
                                </div>
                            </div>
                            <!-- /.counter -->

                        </div>
                        <!-- /.fun-fact-two -->
                    </div>

                    
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->
                </div>
                <!-- /.row -->
            </div>
               <h3 class="title wow pixFadeUp" style="visibility: visible; animation-name: pixFadeUp;">
                    World
                </h3>
                <br>
            <div class="countup-wrapper-two">
                <div class="row no-gutters pricing-amount change-subs-duration">
                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-four wow pixFadeUp" data-wow-delay="0.3s" style="visibility: visible; animation-delay: 0.3s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                           
                                <i class="fas fa-ambulance"></i>
                            </div>
                            <div class="counter">
                                <p>New Cases</p>
                            
                                <div class="global">
                                    <h4 class="count">{{info.global_new_cases}}</h4>
                                </div>
                            </div>
                            <!-- /.counter -->
                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->

                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-two wow pixFadeUp" data-wow-delay="0.5s" style="visibility: visible; animation-delay: 0.5s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-hospital-alt"></i>
                            </div>
                            <div class="counter">
                                <p>Total Cases</p>
                             
                                <div class="global">
                                    <h4 class="count">{{info.global_total_cases}}</h4>
                                </div>
                            </div>
                            <!-- /.counter -->

                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->

                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-three wow pixFadeUp" data-wow-delay="0.7s" style="visibility: visible; animation-delay: 0.7s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-bed"></i>
                            </div>
                            <div class="counter">
                                <p>Deaths</p>
                              
                                <div class="global">
                                    <h4 class="count">{{info.global_deaths}}</h4>
                                </div>
                            </div>
                            <!-- /.counter -->

                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->

                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-five wow pixFadeUp" data-wow-delay="0.9s" style="visibility: visible; animation-delay: 0.9s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-procedures"></i>
                            </div>
                            <div class="counter">
                                <p>Total Recovered</p>
                             
                                <div class="global">
                                    <h4 class="count">{{info.global_recovered}}</h4>
                                </div>
                            </div>
                            <!-- /.counter -->

                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->
                </div>
                <!-- /.row -->
            </div>

               <h3 class="title wow pixFadeUp" style="visibility: visible; animation-name: pixFadeUp;">
                    Death vs Recovered
                </h3>
                <br>
            <div class="countup-wrapper-two">
                <div class="row no-gutters pricing-amount change-subs-duration">
                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-four wow pixFadeUp" data-wow-delay="0.3s" style="visibility: visible; animation-delay: 0.3s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-ambulance"></i>
                            </div>
                            <div class="counter">
                                <p>Global Death Precentage</p>
                            
                                <div class="global">
                                    <h4 class="count">{{gDeath}} %</h4>
                                </div>
                            </div>
                            <!-- /.counter -->
                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->

                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-two wow pixFadeUp" data-wow-delay="0.5s" style="visibility: visible; animation-delay: 0.5s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-hospital-alt"></i>
                            </div>
                            <div class="counter">
                                <p>Global Recovered Precentage</p>
                             
                                <div class="global">
                                    <h4 class="count">{{grecovered}} %</h4>
                                </div>
                            </div>
                            <!-- /.counter -->

                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->

                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-three wow pixFadeUp" data-wow-delay="0.7s" style="visibility: visible; animation-delay: 0.7s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-bed"></i>
                            </div>
                            <div class="counter">
                                <p>Sri Lanka Death Precentage</p>
                              
                                <div class="global">
                                    <h4 class="count">{{ldeath}} %</h4>
                                </div>
                            </div>
                            <!-- /.counter -->

                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->

                    <div class="col-lg-3 col-md-6 col-sm-6">
                        <div class="fun-fact-two color-five wow pixFadeUp" data-wow-delay="0.9s" style="visibility: visible; animation-delay: 0.9s; animation-name: pixFadeUp;">
                            <div class="icon-container">
                                <i class="fas fa-procedures"></i>
                            </div>
                            <div class="counter">
                                <p>Global Recovered Precentage</p>
                             
                                <div class="global">
                                    <h4 class="count">{{lrecovered}} %</h4>
                                </div>
                            </div>
                            <!-- /.counter -->

                        </div>
                        <!-- /.fun-fact-two -->
                    </div>
                    <!-- /.col-lg-3 col-md-6 col-sm-6 -->
                </div>
                <!-- /.row -->
            </div>
            <!-- /.countup-wrapper -->

           
        </div>
    
      
  </div>
</template>

<script>
import axios from 'axios'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data () {
    return {
      info: {},
      hospitals: {},
      date: null,
      gDeath: null,
      grecovered: null,
      ldeath: null,
      lrecovered: null
    }
  },
  mounted () {
    this.getData(),
    this.getDateTime()
    this.getPrecentages()
  },
   methods: {
     getData() {
         axios.get("http://hpb.health.gov.lk/api/get-current-statistical").then(({ data }) => (
  
                     this.info = data.data,
                     this.hospitals = data.data.hospital_data
                   ));
     },

     getDateTime(){
       this.date = new Date().toLocaleString()
     },

     getPrecentages(){
       this.gDeath = ((this.info.global_deaths/this.info.global_total_cases) * 100).toFixed(2)
       this.grecovered = ((this.info.global_recovered/this.info.global_total_cases) * 100).toFixed(2)
       this.ldeath = ((this.info.local_deaths/this.info.local_total_cases) * 100).toFixed(2)
       this.lrecovered = ((this.info.local_recovered/this.info.local_total_cases) * 100).toFixed(2)
     }
   },
  created() {
    this.interval = setInterval(() => this.getPrecentages(), 1000);
    this.interval = setInterval(() => this.getData(), 70000);
    this.interval = setInterval(() => this.getDateTime(), 1000);
   },
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
