<svelte:head>
  <script src="/x.js"></script>
</svelte:head>

<h1>upload file example</h1>
<form
  action="https://3003-rayremnant-csvsomething-5eu2qy802f4.ws-eu38.gitpod.io/csv"
  method="POST"
  enctype="multipart/form-data"
>
  <label for="csv">File</label>
  <input name="csv" type="file" />

  <div>
    <button>Convert</button>
  </div>
</form>
