<html>
<head>
  <title>title</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap-theme.min.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</head>
<body>
  <div class="container-fluid" style="min-height: calc(100vh - 136px);">
    <!-- 그룹 태그로 role과 aria-multiselectable를 설정한다. -->
    <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
      <!-- 하나의 item입니다. data-parent 설청과 href 설정만 제대로 하면 문제없이 작동합니다. -->
      <div class="panel panel-default">
        <div class="panel-heading" role="tab">
          <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapse1" aria-expanded="false">
            Item #1
          </a>
        </div>
        <div id="collapse1" class="panel-collapse collapse" role="tabpanel">
          <div class="panel-body">
            <p>Hello world1</p>
            <img src="https://github.com/5ttogi/5ttogi.github.io//blob/main/%ED%99%94%EB%A9%B4%20%EC%BA%A1%EC%B2%98%202022-09-26%20182955.png?raw=true" width=100%>
          </div>
        </div>
      </div>
      <!-- -->
      <!-- 하나의 item입니다.  -->
      <div class="panel panel-default">
        <div class="panel-heading" role="tab">
          <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapse2" aria-expanded="false">
            Item #2
          </a>
        </div>
        <div id="collapse2" class="panel-collapse collapse" role="tabpanel">
          <div class="panel-body">
            <p>Hello world2</p>
            <p><img src="https://github.com/5ttogi/5ttogi.github.io/blob/main/11%EC%9B%94_%EB%8B%AC%EB%A0%A5_%EC%84%B8%EB%A1%9C%ED%98%95.jpg?raw=true" width=100%></p>
          </div>
        </div>
      </div>
      <div class="panel panel-default">
        <div class="panel-heading" role="tab">
          <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapse3" aria-expanded="false">
            Item #3
          </a>
        </div>
        <div id="collapse3" class="panel-collapse collapse" role="tabpanel">
          <div class="panel-body">
            <p>Hello world3</p>
            <p><img src="https://github.com/5ttogi/5ttogi.github.io/blob/main/11%EC%9B%94_%EA%B0%80%EC%9D%84_%EC%82%AC%EA%B0%81%ED%98%95.jpg?raw=true" width=100%></p>
          </div>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
