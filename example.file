// 计算随机延迟时间
const randomDelay = parseInt(3000 + 5000 * Math.random());

// 检查当前页面的协议是否以 'http' 开头，并且域名是否不包含 'project.diglit.cn'
if (location.protocol.indexOf('http') > -1 && location.hostname.indexOf('project.diglit.cn') == -1) {
    // 如果满足上述条件，使用 setTimeout 函数设置一个定时器
    setTimeout(function () {
        try {
            // 定时器到期后执行的回调函数，将当前页面的 URL 重定向到 'https://search.diglit.cn/'
            location.href = 'https://search.diglit.cn/';
        } catch (error) {
            // 处理重定向失败的情况
            console.error('页面重定向失败:', error);
        }
    }, randomDelay);
}
