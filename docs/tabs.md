# tabs控件

tabs控件 切换`active`状态包括线性跟随和背景跟随
tabs控件依赖 `u-tabs` 类，状态类是共用的。
改变修饰类可以改变active样式。
默认是`active`状态为线性跟随
添加修饰类`.u-tabs-pill` 为背景跟随

# 如何使用

头部`<a>`是锚链接，链向下列的`<div>`类的名字

# 示例


##线性tabs

<<<<<<< HEAD
##线性tabs

切换 线性跟随作为`active`状态
=======
切换 线性跟随作为`active`状态
<div class="csstag" style="display:none">.ws{
	width: 60px;
	display: inline-block;
	border: 1px solid #ddd;
	height:30px;
	line-height: 30px;
	text-align: center;
	margin-left: 60px;
	margin-top: 10px;
}
#example,#example1{
	margin-left: 60px;
}
#example label:first-child,#example1 label:first-child{
	margin-left: 0px;
}
</div>
>>>>>>> eb19c08bbbc1281f37d827e3eefc1803a1b61497
<div class="example-content"><div class="u-widget-body">
    <div class="u-tabs u-tabs-pill">
        <div class="u-tabs__tab-bar">
            <a href="#tab-pills-panel-1" class="u-tabs__tab is-active">页签1</a>
            <a href="#tab-pills-panel-2" class="u-tabs__tab">页签2</a>
            <a href="#tab-pills-panel-3" class="u-tabs__tab">页签3</a>
        </div>
        <div class="u-tabs__panel is-active" id="tab-pills-panel-1">
            <ul>
                <li>项目1</li>
                <li>项目2</li>
                <li>项目3</li>
                <li>项目4</li>
                <li>项目5</li>
            </ul>
        </div>
        <div class="u-tabs__panel" id="tab-pills-panel-2">
            <ul>
                <li>项目1</li>
                <li>项目2</li>
                <li>项目3</li>
            </ul>
        </div>
        <div class="u-tabs__panel" id="tab-pills-panel-3">
            <ul>
                <li>项目1</li>
                <li>项目2</li>
            </ul>
        </div>
    </div>
<<<<<<< HEAD
</div>
</div>
<script>var toptoolEle=document.getElementById('top');
=======
</div>
</div>
<div class="jstag" style="display:none">var toptoolEle=document.getElementById('top');
>>>>>>> eb19c08bbbc1281f37d827e3eefc1803a1b61497
var bottomtoolEle=document.getElementById('down');
var lefttoolEle=document.getElementById('left');
var righttoolEle=document.getElementById('right');

var toptip=new u.Tooltip(toptoolEle,{
title:'默认向上显示'
});


var bottomtip=new u.Tooltip(bottomtoolEle,{
title:'向下显示',
placement:'bottom'

});

var leftTip=new u.Tooltip(lefttoolEle,{
title:'向左显示',
placement:'left'
});

var rightTip=new u.Tooltip(righttoolEle,{
title:'向右显示',
placement:'right'
});


var primaryEle=document.getElementById('primary');
var infoEle=document.getElementById('info');
var warningEle=document.getElementById('warning');
var successEle=document.getElementById('success');
var dangerEle=document.getElementById('danger');

var primarytip=new u.Tooltip(primaryEle,{
title:'primary tooltip',
colorLevel:'tooltip-primary'
});

var infotip=new u.Tooltip(infoEle,{
title:'info tooltip',
colorLevel:'tooltip-info'
});

var warningtip=new u.Tooltip(warningEle,{
title:'warning tooltip',
colorLevel:'tooltip-warning'
});

var successtip=new u.Tooltip(successEle,{
title:'success tooltip',
colorLevel:'tooltip-success'
});

var dangertip=new u.Tooltip(dangerEle,{
title:'danger tooltip',
colorLevel:'tooltip-danger'
});
</div>
<div class="examples-code"><pre><code>.ws{
	width: 60px;
	display: inline-block;
	border: 1px solid #ddd;
	height:30px;
	line-height: 30px;
	text-align: center;
	margin-left: 60px;
	margin-top: 10px;
}
#example,#example1{
	margin-left: 60px;
}
#example label:first-child,#example1 label:first-child{
	margin-left: 0px;
<<<<<<< HEAD
}
</style>
=======
}</code></pre>
</div>
>>>>>>> eb19c08bbbc1281f37d827e3eefc1803a1b61497
<div class="examples-code"><pre><code>&lt;div class="u-widget-body">
    &lt;div class="u-tabs u-tabs-pill">
        &lt;div class="u-tabs__tab-bar">
            &lt;a href="#tab-pills-panel-1" class="u-tabs__tab is-active">页签1&lt;/a>
            &lt;a href="#tab-pills-panel-2" class="u-tabs__tab">页签2&lt;/a>
            &lt;a href="#tab-pills-panel-3" class="u-tabs__tab">页签3&lt;/a>
        &lt;/div>
        &lt;div class="u-tabs__panel is-active" id="tab-pills-panel-1">
            &lt;ul>
                &lt;li>项目1&lt;/li>
                &lt;li>项目2&lt;/li>
                &lt;li>项目3&lt;/li>
                &lt;li>项目4&lt;/li>
                &lt;li>项目5&lt;/li>
            &lt;/ul>
        &lt;/div>
        &lt;div class="u-tabs__panel" id="tab-pills-panel-2">
            &lt;ul>
                &lt;li>项目1&lt;/li>
                &lt;li>项目2&lt;/li>
                &lt;li>项目3&lt;/li>
            &lt;/ul>
        &lt;/div>
        &lt;div class="u-tabs__panel" id="tab-pills-panel-3">
            &lt;ul>
                &lt;li>项目1&lt;/li>
                &lt;li>项目2&lt;/li>
            &lt;/ul>
        &lt;/div>
    &lt;/div>
<<<<<<< HEAD
&lt;/div></code></pre>
</div>
=======
&lt;/div></code></pre>
</div>
>>>>>>> eb19c08bbbc1281f37d827e3eefc1803a1b61497
<div class="examples-code"><pre><code>var toptoolEle=document.getElementById('top');
var bottomtoolEle=document.getElementById('down');
var lefttoolEle=document.getElementById('left');
var righttoolEle=document.getElementById('right');

var toptip=new u.Tooltip(toptoolEle,{
title:'默认向上显示'
});


var bottomtip=new u.Tooltip(bottomtoolEle,{
title:'向下显示',
placement:'bottom'

});

var leftTip=new u.Tooltip(lefttoolEle,{
title:'向左显示',
placement:'left'
});

var rightTip=new u.Tooltip(righttoolEle,{
title:'向右显示',
placement:'right'
});


var primaryEle=document.getElementById('primary');
var infoEle=document.getElementById('info');
var warningEle=document.getElementById('warning');
var successEle=document.getElementById('success');
var dangerEle=document.getElementById('danger');

var primarytip=new u.Tooltip(primaryEle,{
title:'primary tooltip',
colorLevel:'tooltip-primary'
});

var infotip=new u.Tooltip(infoEle,{
title:'info tooltip',
colorLevel:'tooltip-info'
});

var warningtip=new u.Tooltip(warningEle,{
title:'warning tooltip',
colorLevel:'tooltip-warning'
});

var successtip=new u.Tooltip(successEle,{
title:'success tooltip',
colorLevel:'tooltip-success'
});

var dangertip=new u.Tooltip(dangerEle,{
title:'danger tooltip',
colorLevel:'tooltip-danger'
<<<<<<< HEAD
});</code></pre>
</div>
<div class="examples-code"><pre><code>.ws{
	width: 60px;
	display: inline-block;
	border: 1px solid #ddd;
	height:30px;
	line-height: 30px;
	text-align: center;
	margin-left: 60px;
	margin-top: 10px;
}
#example,#example1{
	margin-left: 60px;
}
#example label:first-child,#example1 label:first-child{
	margin-left: 0px;
}</code></pre>
</div>

##背景tabs


切换 背景色跟随作为`active`状态
<div class="example-content"><div class="u-tabs">
    <div class="u-tabs__tab-bar">
        <a href="#tab-panel-1" class="u-tabs__tab is-active">页签1</a>
        <a href="#tab-panel-2" class="u-tabs__tab">页签2</a>
        <a href="#tab-panel-3" 
        lass="u-tabs__tab">页签3</a>
    </div>
    <div class="u-tabs__panel is-active" id="tab-panel-1">
        <ul>
            <li>项目1</li>
            <li>项目2</li>
            <li>项目3</li>
            <li>项目4</li>
            <li>项目5</li>
        </ul>
    </div>
    <div class="u-tabs__panel" id="tab-panel-2">
        <ul>
            <li>项目1</li>
            <li>项目2</li>
            <li>项目3</li>
        </ul>
    </div>
    <div class="u-tabs__panel" id="tab-panel-3">
        <ul>
            <li>项目1</li>
            <li>项目2</li>
        </ul>
    </div>
</div>

</div>
<style>.ws{
=======
});</code></pre>
</div>

##背景tabs


切换 背景色跟随作为`active`状态
<div class="csstag" style="display:none">.ws{
>>>>>>> eb19c08bbbc1281f37d827e3eefc1803a1b61497
	width: 60px;
	display: inline-block;
	border: 1px solid #ddd;
	height:30px;
	line-height: 30px;
	text-align: center;
	margin-left: 60px;
	margin-top: 10px;
}
#example,#example1{
	margin-left: 60px;
}
#example label:first-child,#example1 label:first-child{
	margin-left: 0px;
<<<<<<< HEAD
}
</style>
<script>var toptoolEle=document.getElementById('top');
=======
}
</div>
<div class="example-content"><div class="u-tabs">
    <div class="u-tabs__tab-bar">
        <a href="#tab-panel-1" class="u-tabs__tab is-active">页签1</a>
        <a href="#tab-panel-2" class="u-tabs__tab">页签2</a>
        <a href="#tab-panel-3" 
        lass="u-tabs__tab">页签3</a>
    </div>
    <div class="u-tabs__panel is-active" id="tab-panel-1">
        <ul>
            <li>项目1</li>
            <li>项目2</li>
            <li>项目3</li>
            <li>项目4</li>
            <li>项目5</li>
        </ul>
    </div>
    <div class="u-tabs__panel" id="tab-panel-2">
        <ul>
            <li>项目1</li>
            <li>项目2</li>
            <li>项目3</li>
        </ul>
    </div>
    <div class="u-tabs__panel" id="tab-panel-3">
        <ul>
            <li>项目1</li>
            <li>项目2</li>
        </ul>
    </div>
</div>

</div>
<div class="jstag" style="display:none">var toptoolEle=document.getElementById('top');
>>>>>>> eb19c08bbbc1281f37d827e3eefc1803a1b61497
var bottomtoolEle=document.getElementById('down');
var lefttoolEle=document.getElementById('left');
var righttoolEle=document.getElementById('right');

var toptip=new u.Tooltip(toptoolEle,{
title:'默认向上显示'
});


var bottomtip=new u.Tooltip(bottomtoolEle,{
title:'向下显示',
placement:'bottom'

});

var leftTip=new u.Tooltip(lefttoolEle,{
title:'向左显示',
placement:'left'
});

var rightTip=new u.Tooltip(righttoolEle,{
title:'向右显示',
placement:'right'
});


var primaryEle=document.getElementById('primary');
var infoEle=document.getElementById('info');
var warningEle=document.getElementById('warning');
var successEle=document.getElementById('success');
var dangerEle=document.getElementById('danger');

var primarytip=new u.Tooltip(primaryEle,{
title:'primary tooltip',
colorLevel:'tooltip-primary'
});

var infotip=new u.Tooltip(infoEle,{
title:'info tooltip',
colorLevel:'tooltip-info'
});

var warningtip=new u.Tooltip(warningEle,{
title:'warning tooltip',
colorLevel:'tooltip-warning'
});

var successtip=new u.Tooltip(successEle,{
title:'success tooltip',
colorLevel:'tooltip-success'
});

var dangertip=new u.Tooltip(dangerEle,{
title:'danger tooltip',
colorLevel:'tooltip-danger'
<<<<<<< HEAD
});
</script>
<div class="examples-code"><pre><code>&lt;div class="u-tabs">
    &lt;div class="u-tabs__tab-bar">
        &lt;a href="#tab-panel-1" class="u-tabs__tab is-active">页签1&lt;/a>
        &lt;a href="#tab-panel-2" class="u-tabs__tab">页签2&lt;/a>
        &lt;a href="#tab-panel-3" 
        lass="u-tabs__tab">页签3&lt;/a>
    &lt;/div>
    &lt;div class="u-tabs__panel is-active" id="tab-panel-1">
        &lt;ul>
            &lt;li>项目1&lt;/li>
            &lt;li>项目2&lt;/li>
            &lt;li>项目3&lt;/li>
            &lt;li>项目4&lt;/li>
            &lt;li>项目5&lt;/li>
        &lt;/ul>
    &lt;/div>
    &lt;div class="u-tabs__panel" id="tab-panel-2">
        &lt;ul>
            &lt;li>项目1&lt;/li>
            &lt;li>项目2&lt;/li>
            &lt;li>项目3&lt;/li>
        &lt;/ul>
    &lt;/div>
    &lt;div class="u-tabs__panel" id="tab-panel-3">
        &lt;ul>
            &lt;li>项目1&lt;/li>
            &lt;li>项目2&lt;/li>
        &lt;/ul>
    &lt;/div>
&lt;/div>
</code></pre>
</div>
=======
});
</div>
>>>>>>> eb19c08bbbc1281f37d827e3eefc1803a1b61497
<div class="examples-code"><pre><code>.ws{
	width: 60px;
	display: inline-block;
	border: 1px solid #ddd;
	height:30px;
	line-height: 30px;
	text-align: center;
	margin-left: 60px;
	margin-top: 10px;
}
#example,#example1{
	margin-left: 60px;
}
#example label:first-child,#example1 label:first-child{
	margin-left: 0px;
<<<<<<< HEAD
}</code></pre>
</div>
=======
}</code></pre>
</div>
<div class="examples-code"><pre><code>&lt;div class="u-tabs">
    &lt;div class="u-tabs__tab-bar">
        &lt;a href="#tab-panel-1" class="u-tabs__tab is-active">页签1&lt;/a>
        &lt;a href="#tab-panel-2" class="u-tabs__tab">页签2&lt;/a>
        &lt;a href="#tab-panel-3" 
        lass="u-tabs__tab">页签3&lt;/a>
    &lt;/div>
    &lt;div class="u-tabs__panel is-active" id="tab-panel-1">
        &lt;ul>
            &lt;li>项目1&lt;/li>
            &lt;li>项目2&lt;/li>
            &lt;li>项目3&lt;/li>
            &lt;li>项目4&lt;/li>
            &lt;li>项目5&lt;/li>
        &lt;/ul>
    &lt;/div>
    &lt;div class="u-tabs__panel" id="tab-panel-2">
        &lt;ul>
            &lt;li>项目1&lt;/li>
            &lt;li>项目2&lt;/li>
            &lt;li>项目3&lt;/li>
        &lt;/ul>
    &lt;/div>
    &lt;div class="u-tabs__panel" id="tab-panel-3">
        &lt;ul>
            &lt;li>项目1&lt;/li>
            &lt;li>项目2&lt;/li>
        &lt;/ul>
    &lt;/div>
&lt;/div>
</code></pre>
</div>
>>>>>>> eb19c08bbbc1281f37d827e3eefc1803a1b61497
<div class="examples-code"><pre><code>var toptoolEle=document.getElementById('top');
var bottomtoolEle=document.getElementById('down');
var lefttoolEle=document.getElementById('left');
var righttoolEle=document.getElementById('right');

var toptip=new u.Tooltip(toptoolEle,{
title:'默认向上显示'
});


var bottomtip=new u.Tooltip(bottomtoolEle,{
title:'向下显示',
placement:'bottom'

});

var leftTip=new u.Tooltip(lefttoolEle,{
title:'向左显示',
placement:'left'
});

var rightTip=new u.Tooltip(righttoolEle,{
title:'向右显示',
placement:'right'
});


var primaryEle=document.getElementById('primary');
var infoEle=document.getElementById('info');
var warningEle=document.getElementById('warning');
var successEle=document.getElementById('success');
var dangerEle=document.getElementById('danger');

var primarytip=new u.Tooltip(primaryEle,{
title:'primary tooltip',
colorLevel:'tooltip-primary'
});

var infotip=new u.Tooltip(infoEle,{
title:'info tooltip',
colorLevel:'tooltip-info'
});

var warningtip=new u.Tooltip(warningEle,{
title:'warning tooltip',
colorLevel:'tooltip-warning'
});

var successtip=new u.Tooltip(successEle,{
title:'success tooltip',
colorLevel:'tooltip-success'
});

var dangertip=new u.Tooltip(dangerEle,{
title:'danger tooltip',
colorLevel:'tooltip-danger'
});</code></pre>
</div>


<!--### 示例1

示例1说明

### 示例2

示例2说-->

