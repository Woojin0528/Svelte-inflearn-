<script>
	import {storeName} from './store.js'
	//store�|  �� (�
	import Parent from './Parent.svelte'
	
	let name = 'world';
	$storeName = name
	//t� storeName� name(world)| `�\� t t nameD ����  ��0L8� nameD ��`  ��.
// 	console.log(storeName)
	//console��t set, update,subscribe 3X T��  �(�. �� T��.
// 	console.log($storeName)
	// $08| h storeNameX pt0| �%\�. �@ H 8��\ t� X�=��� pt0  H�.
	//tx quto-subscribtiont|�\�.
</script>

<h1>Hello {name}!</h1>
<Parent/>

<!--И� app.-Parent.-child.<\ ���� �  ��<\ 1� namet|� �|  <Parent/>� propsP<\ `�X�, app.svelteX name�| childL� �$ ��`  ��p, t�Xt t  �  ��X� �DLDL �X0 ���\ store|� x�� |� �x ��\�. -->