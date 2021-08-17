<template>

  <!-- page content -->
  <div class="grid m-10 place-content-center h-96 bg-base-200">
    <a href="#my-anchor-modal" class="btn btn-primary">Open Modal 1</a>
  </div>

  <div class="grid m-10 place-content-center h-96 bg-base-200">
    <label for="my-checkbox-modal" class="btn btn-primary modal-button">Open Modal 2</label> 
  </div>
  <div class="grid m-10 place-content-center h-96 bg-base-200">long content</div>
  <div class="grid m-10 place-content-center h-96 bg-base-200">long content</div>
  <div class="grid m-10 place-content-center h-96 bg-base-200">long content</div>


  <!-- modal 1 using anchor link -->  
  <div>
    <div id="my-anchor-modal" class="modal">
      <div class="modal-box">
        <p>Enim dolorem dolorum omnis atque necessitatibus. Consequatur aut adipisci qui iusto illo eaque. Consequatur repudiandae et. Nulla ea quasi eligendi. Saepe velit autem minima.</p> 
        <div class="modal-action">
          <a href="#" class="btn btn-primary">Accept</a> 
          <a href="#" class="btn">Close</a>
        </div>
      </div>
    </div>
  </div>

  <!-- modal 2 using hidden checkbox -->
  <div>
    <input type="checkbox" id="my-checkbox-modal" class="modal-toggle">
    <div class="modal">
      <div class="modal-box">n
        <p>Enim dolorem dolorum omnis atque necessitatibus. Consequatur aut adipisci qui iusto illo eaque. Consequatur repudiandae et. Nulla ea quasi eligendi. Saepe velit autem minima.</p>
        <div class="modal-action">
          <label for="my-checkbox-modal" class="btn btn-primary">Accept</label>
          <label for="my-checkbox-modal" class="btn">Close</label>
        </div>
      </div>
    </div>
  </div>



</template>