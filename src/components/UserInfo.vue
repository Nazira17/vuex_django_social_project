<template>
    <div class="row mb-3">
        <div class="col-md-6">
            <div class="d-flex flex-row border rounded">
                <div class="p-0 w-25">
                    <img src="https://c1.staticflickr.com/3/2862/12328317524_18e52b5972_k.jpg" class="img-thumbnail border-0" />
                </div>
                <div class="pl-3 pt-2 pr-2 pb-2 w-75 border-left">
                        <h4 class="text-primary">{{ user.username }}</h4>
                        Followers: <h5 class="text-info">{{ user.followers }}</h5>
                        Following: <h5 class="text-info">{{ user.following }}</h5>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'userinfo',
  props: ['user'],
};
</script>
