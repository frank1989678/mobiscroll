# mobiscroll
参考资料 
<br>1: http://www.myexception.cn/web/1915230.html
<br>2: http://www.cnblogs.com/headwolf/archive/2013/12/23/3487207.html


<table>
    <thead>
        <tr>
            <th>参数</th>
            <th>说明</th>
            <th>默认值</th>
            <th>参数类型</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>mode</td>
            <td>模式(滚动/点击/混合)
            	<br>scroller —— 以wheel滑动方式选择
				<br>clickpick —— 显示 - + 按钮选择
				<br>mixed —— 兼容以上两种方式
 			</td>
            <td>scroller</td>
            <td>String</td>
        </tr>
        <tr>
            <td>display</td>
            <td>显示形式
            	<br>modal —— 拾取
				<br>inline —— 直接
				<br>bubble —— 气泡
				<br>bottom —— 底部
 			</td>
            <td>modal</td>
            <td>String</td>
        </tr>
        <tr>
            <td>animation</td>
            <td>动画
            	<br>slideup —— 从下滑出
 			</td>
            <td>无</td>
            <td>String</td>
        </tr>
        <tr>
            <td>invalid</td>
            <td>无效日期
            	<br>eg:{ daysOfWeek: [0, 6], daysOfMonth: ['5/1', '12/24', '12/25'] },
 			</td>
            <td>无</td>
            <td>Object</td>
        </tr>
        <tr>
            <td>showLabel</td>
            <td>显示标题（年/月/日/时/分）：
            	<br>false —— 不显示
            	<br>true —— 显示
 			</td>
            <td>false</td>
            <td>Boolean</td>
        </tr>
        <tr>
            <td>onSelect</td>
            <td>确定按钮回调</td>
            <td>无</td>
            <td>Function</td>
        </tr>
        <tr>
            <td>onCancel</td>
            <td>取消按钮回调</td>
            <td>无</td>
            <td>Function</td>
        </tr>
        <tr>
            <td>onClose</td>
            <td>当弹出效果退出的时候执行该方法，在onSelect 和 onCancel之前执行</td>
            <td>无</td>
            <td>Function</td>
        </tr>
    </tbody>
</table>

