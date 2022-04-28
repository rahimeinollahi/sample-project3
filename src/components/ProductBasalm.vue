<template>
    <div class="container">
        <div class=" text-start">
            <h6>- Name and Classification</h6>

               
                <form class="card w-50 m-2 p-4">
                    <div class="form-check">
                        <label for="product-name" >your product name</label>
                        <input type="text" value="productname" id="product-name" placeholder="Enter productName" class="form-control" maxlength="10">
                    <input type="radio" class="form-check-input" id="radio1" name="optradio" value="option1" checked>
                    <label for="radio1" class="form-check-label">Service of Product</label>
                    </div>
                 </form>

                 <div class="card w-50 mt-3 p-5">
                     <span class="inline-block">Write detail about product name</span>
                     <form action="" method="get">
                         <label for="file-name">Choose file</label>
                         <input type="text" class="form-control" id="file-name" name="file-name">
                         <input type="file" class="mt-3">
                     </form>
                 </div>

                 <div class="card">
                     <form action="" class="p-3">
                         <label for="sel1" class="form-label">form select</label>

                         <select name="sellist1" id="sel1" class="form-select" >
                             <option>All</option>
                             <option>Not All</option>
                         </select>
                            <div class="inline-block">Send to Area</div>

                            <div class="form-check">
                                <input type="radio" class="form-check-input" id="radio2" name="optradio" value="option2">
                                <label class="form-check-label" for="radio2">Option 2</label>
                            </div>

                            <div class="form-check">
                                <input type="radio" class="form-check-input" id="radio2" name="optradio" value="option2">
                                <label class="form-check-label" for="radio2">Option 2</label>
                            </div>

                            <button class="btn btn-info mt-3 p1">Save Info</button>
                     </form>
                 </div>
        </div>
    </div>
</template>

<script>
    export default {
        name:'CreateProduct'
    }
</script>

<style lang="scss" scoped>

</style>