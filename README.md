获取当前日期的农历。

调用方法：
import cnDate from 'commonjs/cnDate.js';

getCnDate: function () {
    let d = new Date();
    let yy = d.getFullYear();
    let mm = d.getMonth() + 1;
    let dd = d.getDate();
    this.currLanur = cnDate.getDate(yy, mm, dd)
}
    