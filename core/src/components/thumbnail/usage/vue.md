```html
<template>
  <ion-thumbnail>
    <img src="https://gravatar.com/avatar/dba6bae8c566f9d4041fb9cd9ada7741?d=identicon&f=y">
  </ion-thumbnail>

  <ion-item>
    <ion-thumbnail slot="start">
      <img src="https://gravatar.com/avatar/dba6bae8c566f9d4041fb9cd9ada7741?d=identicon&f=y">
    </ion-thumbnail>
    <ion-label>Item Thumbnail</ion-label>
  </ion-item>
</template>

<script>
import { IonItem, IonLabel, IonThumbnail } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  components: { IonItem, IonLabel, IonThumbnail }
});
</script>
```