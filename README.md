# ecms
没有描述
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>操作日志</title>
<script type="text/javascript" src="../../psresources/js/base/ps.js"></script>
<script type="text/javascript">
	ps.res.load("jqgrid");
	ps.res.load("bootstrap_dialog");
	ps.res.load("font_awesome");
	ps.res.load("ztree");
	ps.res.load("module/log/log-manage.js");
	ps.res.load("module/log/log-manage.css");
	ps.res.load("css/tree-icon.css");
</script>
</head>
<body>
	<div class="wrapper">
		<div class="div_tree">
			<div class="div_tree_title">
				<i class="fa fa-pencil fa-fw"></i>
				操作日志
			</div>
			<ul id="ztree" class="ztree"></ul>
		</div>
		<div class="div_grid">
			<table id="grid"></table>
			<div id="pager"></div>
		</div>
	</div>

</body>
</html>
