Lorem Ipsum
===========
_"Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit..."_
_"There is no one who loves pain itself, who seeks after it and wants to have it, simply because it is pain..."_

---

<div id="app">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla urna nisi, pellentesque at risus vitae, posuere ultrices magna. Donec rhoncus nisl ac enim aliquet dapibus. Vestibulum tincidunt enim quis viverra fermentum. Aenean nec nulla eget sapien ultrices tincidunt ac eget nisi. Etiam eu luctus mauris. Sed iaculis imperdiet felis, a semper mi placerat vitae. Etiam molestie erat ut urna condimentum finibus. Morbi venenatis, est sit amet lobortis egestas, quam est mattis nisl, quis maximus lectus mauris eu enim. Pellentesque tincidunt vel orci ut mollis. Curabitur luctus, augue quis tincidunt tristique, risus tortor luctus leo, vitae consectetur augue magna id dolor. Integer id enim mauris. Duis dignissim luctus sapien, ac eleifend ex volutpat vel.

> Nam finibus lacinia nisl nec blandit. Phasellus semper risus eu porttitor blandit. Sed sem libero, malesuada sed ligula eu, euismod pharetra arcu. Phasellus laoreet elementum nulla sit amet volutpat. Nullam eu malesuada ipsum. Nullam sit amet cursus neque. Donec nec mattis nisl, in feugiat magna. Donec enim lectus, facilisis eu blandit ut, ornare in nisi. Nullam mollis ultricies purus, ut sagittis risus. Suspendisse potenti. Mauris porttitor, sem quis interdum sagittis, est diam aliquet purus, non dictum felis enim dapibus diam.

Maecenas tempor justo id arcu viverra dictum. Ut et viverra purus. Aenean interdum blandit elit, a faucibus mi eleifend non. Vestibulum viverra, purus ut laoreet posuere, augue est volutpat orci, at viverra lacus massa non tortor. Mauris nec imperdiet eros. Curabitur sit amet ligula et neque hendrerit ultrices. Maecenas leo ipsum, pharetra fringilla velit et, tempor cursus lectus. Ut vel nibh et lacus tincidunt venenatis nec sit amet ligula.

> Suspendisse tincidunt arcu id enim cursus congue. Mauris volutpat nec leo sodales consequat. Donec feugiat dignissim sapien id placerat. Sed consequat diam ac est tempus, vel interdum lacus efficitur. Ut scelerisque nisl eros, et congue augue mattis eget. Mauris auctor metus eget suscipit sodales. Cras laoreet dolor vel purus lobortis, ac elementum tellus mattis. Fusce euismod, libero in auctor rhoncus, sem augue dapibus dui, eu consequat quam sapien eu arcu. Maecenas eget urna nec risus tempus finibus sed quis erat. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dui urna, molestie eget aliquam vitae, ultricies eu sapien. Aliquam ornare sodales ipsum, id volutpat nulla varius tempor. Duis sagittis sed mi volutpat luctus.

Phasellus ullamcorper pharetra iaculis. In malesuada lacus eget velit aliquet, vel pulvinar ante mollis. Morbi pharetra est ultrices risus rutrum aliquam. Aliquam erat volutpat. Integer eu leo dui. Donec iaculis blandit velit, quis efficitur mi venenatis eu. Mauris dapibus et leo at elementum. 
{{ message }}
</div>

<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
<script>
  const { createApp, ref } = Vue

  createApp({
    setup() {
      const message = ref('Hello vue!')
      return {
        message
      }
    }
  }).mount('#app')
</script>