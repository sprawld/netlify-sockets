<script>
  
  fetch('/api/hello')
    .then(res => res.text())
    .then(res => console.log('succeeded', res), err => console.error('failed', err));

</script>

<h1>Hello World</h1>
