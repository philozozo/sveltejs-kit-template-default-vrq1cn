<script>

let url='http://82.65.219.10:81/web/0api/api.php/'
let base = 'gl/gap17/' 
let all = {}
async function fetchData() {

  const res = await fetch(
    url+base,{credentials: "include"}
  )
  all = await res.json()

}

fetchData()



</script>




<div>


	<p>
base = {base}
<br>
all = {all}
	</p>
</div>