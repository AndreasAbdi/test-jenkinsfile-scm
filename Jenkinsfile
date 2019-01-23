@Library('outsider')
import org.test.Bar
import org.test.Configurer

node {
   echo 'Hello World'
   println "yoohoo"
   Bar bar = new Bar()
   println bar.class
   Configurer configurer = new Configurer(this)
   configurer.configure()
}