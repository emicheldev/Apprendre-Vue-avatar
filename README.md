# Apprendre à utliser Vue-avatar

Vue avatar est un composant d'avatar pour vue.js.

> Parfois nous voulons afficher les avatar facilement sur nos site
> ces avatars peuvent être des images en png, jpg ou en svg.
> Vue avatar va plus loin en utlisant les initiales de l'utilisateur.
> 

### Comment travailler avec vue-avatar

1. Installer vue.Js
2. Installer vue-avatar
```npm install vue-avatar```
3. impoter vue-avata 
```
<script>
//impoter vue-avatar
import Avatar from 'vue-avatar'
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    Avatar
  },
}
</script>
```
