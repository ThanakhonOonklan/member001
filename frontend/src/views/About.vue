<template>
  <div class="about text-center">
    <h1>This is an abount page</h1>
    <div class="dropdown">
  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    รูปนักศึกษาโปรเเกรมเมอร์
  </button>
  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
    <a class="dropdown-item" href="Vocational1">ปวช.1</a>
    <a class="dropdown-item" href="Vocational2">ปวช.2</a>
    <a class="dropdown-item" href="Vocational3">ปวส.1</a>
    <a class="dropdown-item" href="Vocational4">ปวส.2</a>
    <a class="dropdown-item" href="Vocational5">ศิษย์เก่า</a>
  </div>
</div>
<button type="button" class="btn btn-secondary" data-container="body" data-toggle="popover" data-placement="top" data-content="Vivamus sagittis lacus vel augue laoreet rutrum faucibus.">
  Popover on top
</button>
<button type="button" class="btn btn-secondary" data-container="body" data-toggle="popover" data-placement="right" data-content="Vivamus sagittis lacus vel augue laoreet rutrum faucibus.">
  Popover on right
</button>
<button type="button" class="btn btn-secondary" data-container="body" data-toggle="popover" data-placement="bottom" data-content="Vivamus
sagittis lacus vel augue laoreet rutrum faucibus.">
  Popover on bottom
</button>
<button type="button" class="btn btn-secondary" data-container="body" data-toggle="popover" data-placement="left" data-content="Vivamus sagittis lacus vel augue laoreet rutrum faucibus.">
  Popover on left
</button>
  </div>
</template>
<style scoped>
button {
  margin: 5px;
}
</style>