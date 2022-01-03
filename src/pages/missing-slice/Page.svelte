<style>
  .frame {
    background: #e3516e;
    width: 400px;
    height: 300px;
  }
  .pie {
    position: relative;
    left: 90px;
    top: 40px;
    width: 100px;
    height: 100px;
  }
  .top-left {
    background: #51b5a9;
    border-top-left-radius: 100px;
  }
  .bottom-left {
    background: #f7f3d7;
    border-bottom-left-radius: 100px;
  }
  .top-right {
    background: #fade8b;
    border-top-right-radius: 100px;
    transform: translate(100px, -200px);
  }

</style>

<div class="frame">
  <div class="pie top-left" />
  <div class="pie bottom-left" />
  <div class="pie top-right" />
</div>
