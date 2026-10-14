<script>
    let message;
    fetch("http://127.0.0.1:8000/hello").then((response) => { 
        response.json().then((json) => {
            message = json.message; 
    });
    }); 
</script>

<h1>안녕하세요 파이보</h1>