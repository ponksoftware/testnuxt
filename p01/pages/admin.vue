<template>
   <div>
           <form>
               <div class="form-group col-lg-2 "> 
                    <label>Form User Admin Extranal</label>
               <input type = "text" class="form-control" >           
              
               <br>
                <input type ="submit" value="insert" class="btn btn-primary">
            </div> 
           </form>
               
           <nuxt-child/>
  
   </div>
    
</template>

<script>
export default {
  layout: 'newLayout'
}
</script>