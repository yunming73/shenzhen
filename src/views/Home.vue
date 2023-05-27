<template>
  <div class="container">
    <div class="top">
      <!-- 顶部内容 -->
      <nav>
        <ul>
          <li><a href="#">English</a></li>
          <li><a href="#">学生</a></li>
          <li><a href="#">教工</a></li>
          <li><a href="#">访客</a></li>
          <li><a href="#">手机版</a></li>
        </ul>
        <ul>
          <li><a href="#">教师邮箱</a></li>
          <li><a href="#">学生邮箱</a></li>
          <li>
            <a href="#"><img src="../assets/img/1684984643.png" /></a>
          </li>
        </ul>
      </nav>
    </div>
    <header class="header">
      <!-- 头部内容 -->
      <div class="header-content">
        <div class="logo">
          <a href="#">
            <img src="../assets/img/1684984644.png" alt="" />
          </a>
        </div>
        <div class="menu">
          <ul>
            <li>
              <h2><a href="#">学校概况</a></h2>
            </li>
          </ul>
          <ul>
            <li>
              <h2><a href="#">学院设置</a></h2>
            </li>
          </ul>
          <ul>
            <li>
              <h2><a href="#">教育教学</a></h2>
            </li>
          </ul>
          <ul>
            <li>
              <h2><a href="#">科学研究</a></h2>
            </li>
          </ul>
          <ul>
            <li>
              <h2><a href="#">招生计划</a></h2>
            </li>
          </ul>
          <ul>
            <li>
              <h2><a href="#">国际交流</a></h2>
            </li>
          </ul>
          <ul>
            <li>
              <h2><a href="#">图书馆</a></h2>
            </li>
          </ul>
          <ul>
            <li>
              <h2><a href="#">校园生活</a></h2>
            </li>
          </ul>
        </div>
      </div>
    </header>
    <nav class="navigation">
      <!-- 导航内容 -->
      <div class="news">
        <!-- 轮播图 -->
        <div class="news-top">
          <span class="news-top-icon-left"></span>
          <span class="news-top-icon-right"></span>
        </div>
        <!-- 日期 -->
        <div class="news-bottom">
          <div class="news-bottom-top">
            <div class="news-bottom-top-left"><a href="#"></a>4月</div>
            <div class="news-bottom-top-data">
              <a href="#">学习贯彻习近平新时代中国特色社会主义思想主题教育</a>
            </div>
            <div class="news-bottom-top-right">2023年5月25日</div>
          </div>
          <div class="news-bottom-bottom">
            <ul>
              <li v-for="(item, i) in NewsDate" :key="i">
                <span tabindex="0">{{ item }}</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </nav>
    <section class="main">
      <!-- 主要内容区域 -->
      <div class="main-one">
        <div class="main-one-left">
          <!-- 标题 -->
          <div class="main-one-left-title">
            <span>
              <a href="#">
                <img src="../assets/img/more_jiantou.png" alt="" /></a></span
            ><img src="../assets/img/1684984659.png" /><i>深职要闻</i>
          </div>
          <!-- 内容 -->
          <div class="main-one-left-box">
            <div class="main-one-left-box-top">
              <ul>
                <li>
                  <a href="#">
                    <img src="../assets/img/1684984660.jpg" />
                  </a>
                  <a href="#"
                    >学校选手在广东省第三届职业技能大赛中勇夺5金3银3铜1优胜奖</a
                  >
                </li>
                <li>
                  <a href="#">
                    <img src="../assets/img/1684984662.jpg" />
                  </a>
                  <a href="#">开门红！汽车学子获国赛汽车故障检修赛项一等奖</a>
                </li>
              </ul>
            </div>
            <div class="main-one-left-box-bottom">
              <ul>
                <li>
                  <a href="#"
                    >学校选手在广东省第三届职业技能大赛中勇夺5金3...</a
                  >
                </li>
                <li>
                  <a href="#"
                    >学校选手在广东省第三届职业技能大赛中勇夺5金3...</a
                  >
                </li>
                <li>
                  <a href="#"
                    >学校选手在广东省第三届职业技能大赛中勇夺5金3...</a
                  >
                </li>
                <li>
                  <a href="#"
                    >学校选手在广东省第三届职业技能大赛中勇夺5金3...</a
                  >
                </li>
                <li>
                  <a href="#"
                    >学校选手在广东省第三届职业技能大赛中勇夺5金3...</a
                  >
                </li>
                <li>
                  <a href="#"
                    >学校选手在广东省第三届职业技能大赛中勇夺5金3...</a
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="main-one-right">
          <div class="main-one-right-top">
            <!-- 标题 -->
            <div class="main-one-left-title">
              <span>
                <a href="#">
                  <img src="../assets/img/more_jiantou.png" alt="" /></a></span
              ><img src="../assets/img/1684984664.png" /><i>媒体看深职</i>
            </div>
            <div class="main-one-right-top-content">
              <ul>
                <li>
                  <a href="#"
                    >[央视新闻]朝闻天下-新360行 新机遇 加快康复辅...</a
                  >
                  <span>04.03</span>
                </li>
                <li>
                  <a href="#"
                    >[央视新闻]朝闻天下-新360行 新机遇 加快康复辅...</a
                  >
                  <span>04.03</span>
                </li>
                <li>
                  <a href="#"
                    >[央视新闻]朝闻天下-新360行 新机遇 加快康复辅...</a
                  >
                  <span>04.03</span>
                </li>
              </ul>
            </div>
          </div>
          <div class="main-one-right-bottom">
            <!-- 标题 -->
            <div class="main-one-left-title">
              <span>
                <a href="#">
                  <img src="../assets/img/more_jiantou.png" alt="" /></a></span
              ><img src="../assets/img/1684984666.png" /><i>公告通知</i>
            </div>
            <div class="main-one-right-content">
              <ul>
                <li>
                  <RouterLink to="/info">
                    2023～2024学年度第一学期
                    校级选修课（通识一般）选课通知</RouterLink
                  >
                  <span>05.23</span>
                </li>
                <li>
                  <RouterLink to="/info">
                    2023～2024学年度第一学期
                    校级选修课（通识一般）选课通知</RouterLink
                  >
                  <span>05.23</span>
                </li>
                <li>
                  <RouterLink to="/info">
                    2023～2024学年度第一学期
                    校级选修课（通识一般）选课通知</RouterLink
                  >
                  <span>05.23</span>
                </li>
                <li>
                  <RouterLink to="/info">
                    2023～2024学年度第一学期
                    校级选修课（通识一般）选课通知</RouterLink
                  >
                  <span>05.23</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="main-two">
        <div class="main-two-hd">
          <ul>
            <li>
              <a href="#">
                人才培养
                <img src="../assets/img/tab_icon_fg.png" />
                <i>EDUCATION</i>
              </a>
            </li>
            <li>
              <a href="#">
                科学研究
                <img src="../assets/img/tab_icon_fg.png" />
                <i>RESEARCH</i>
              </a>
            </li>
            <li>
              <a href="#">
                国际交流
                <img src="../assets/img/tab_icon_fg.png" />
                <i>INTERNATIONAL</i>
              </a>
            </li>
          </ul>
        </div>
        <div class="main-two-bd">
          <ul>
            <li>
              <a href="#"> <img src="../assets/img/1684984671.jpg" /></a>
              <div class="txt">
                <a href="#">连续4年全球金奖！深职学子在iGEM大赛再夺佳绩</a>
                <p>
                  获奖团队合影。10月28日结束的国际基因工程机器大赛International
                  Genetically Engineered Machine
                  Competition（iGEM）中，由我校材环学院精细化工技术专业老师隗晶晶、刘红波指导，商...
                </p>
                <a class="txt-a">
                  <img src="../assets/img/more_02.png" />
                </a>
              </div>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/1684984686.png" />
              </a>
              <div class="txt">
                <a href="#"> 国际网络教育学院（IIOE）在云端发布 </a>
                <img src="../assets/img/1684984674.png" alt="" />
              </div>
            </li>
            <li>
              <a href="#"><img src="../assets/img/1684984687.jpg" alt="" /></a>
              <div class="txt">
                <a href="#"> 南非Southern LABS及华为代表团来校访问 </a>
              </div>
            </li>
            <li>
              <a href="#"><img src="../assets/img/1684984688.jpg" alt="" /></a>
              <div class="txt">
                <a href="#"> 学校举行多糖科学及保健和生物材料应用国际会议 </a>
              </div>
            </li>
            <li>
              <a href="#"><img src="../assets/img/1684984689.jpg" alt="" /></a>
              <div class="txt">
                <a href="#"> 我校与教科文高等教育创新中心签署合作意向书 </a>
              </div>
            </li>
            <li>
              <a href="#"><img src="../assets/img/1684984690.jpg" alt="" /></a>
              <div class="txt">
                <a href="#">
                  马来西亚雪兰莪货运及物流报关行协会总会长拿督谢汉廷一行来...
                </a>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div class="main-link">
        <div class="main-link-scroll">
          <div class="main-link-scroll-hd">
            <a href="#" class="next"></a>
            <a href="#" class="prev"></a>
          </div>
          <div class="main-link-scroll-bd">
            <div class="wrap">
              <ul>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
                <li>
                  <div class="pic"><a href="#"> </a></div>
                  <div class="title"><a href="#">招标采购</a></div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
    <footer class="footer">
      <!-- 底部内容 -->
      <div class="footer-top">
        <div class="footer-top-left">
          <a href="#">广东省教育厅</a>
          <a href="#">深圳市教育局</a>
          <a href="#">中国高职高专教育网</a>
          <a href="#">教科文国际职教中心</a>
          <a href="#">深圳市推进粤港澳大湾...</a>
        </div>
        <div class="footer-top-right">
          <ul>
            <li>
              <a href="#"
                ><img src="../assets/img/link_select_1.png" alt="" />
                二级学院网站导航列表</a
              >
            </li>
            <li>
              <a href="#"
                ><img src="../assets/img/link_select_1.png" alt="" />
                职能部门网站导航列表</a
              >
            </li>
          </ul>
        </div>
      </div>
      <div class="footer-mid">
        <div class="footer-mid-logo">
          <img src="../assets/img/1684984713.png" alt="" />
        </div>
        <div class="footer-mid-data">
          <p>学院地址：广东省深圳市南山区留仙大道7098号 邮编：518055</p>
          <p>联系电话：26731000、26019709、26731842 传真：26731712</p>
          <p><br /></p>
          <a href="#"><img src="../assets/img/1684984714.png" alt="" /></a>
          <a href="#"
            ><img
              style="width: 120px"
              src="../assets/img/1684984715.png"
              alt=""
          /></a>
        </div>
        <div class="footer-mid-qr">
          <span>
            <a href="#">
              <img src="../assets/img/1684984716.png" />
            </a>
            <a href="">官方微博</a>
          </span>
          <span>
            <a href="#">
              <img src="../assets/img/1684984717.png" />
            </a>
            <a href="">官方微信</a>
          </span>
        </div>
      </div>
      <div class="footer-bottom">
        <p>Copyright © SHENZHEN POLYTECHNIC. All Rights Reserved 备案号：</p>
        <a href="#">粤ICP备15008843号</a>
        <a href="#">深公网安备4403101901260</a>
        <div class="back">
          <a href="#" @click="totop()"
            >返回顶部<img src="../assets/img/1684984718.png" alt=""
          /></a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import { ref } from "vue";
export default {
  name: "shenzhenHome",
  setup() {
    let NewsDate = ref();
    NewsDate = 30;
    const totop = () => {
      window.scrollTo({ top: 0, behavior: "smooth" });
    };
    // console.log(NewsDate);
    //   const items = ref([
    //     { id: 1, text: "English", imagePath: "../assets/img/1684984643.png" },
    //     { id: 2, text: "学生", imagePath: "../assets/img/1684984637.png" },
    //     { id: 3, text: "教工", imagePath: "../assets/img/1684984643.png" },
    //     { id: 4, text: "访客", imagePath: "../assets/img/1684984637.png" },
    //     { id: 5, text: "手机版", imagePath: "../assets/img/1684984643.png" },
    //   ]);

    return { NewsDate, totop };
  },
};
</script>

<style lang="less" scoped>
.container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  background: url("../assets/img/list_body_bg.png") center top no-repeat #ffffff;
}

.top {
  width: 100%;
  height: 40px;
  background: #bc3b36;
  nav {
    width: 1200px;
    display: flex;
    margin: 0 auto;
    justify-content: space-between;
    ul {
      display: flex;
      li {
        float: left;
        line-height: 40px;
        padding-right: 20px;
        padding-left: 23px;
        a {
          color: #ffffff;
          font-size: 14px;
        }
      }
    }
    ul:first-child {
      li::before {
        content: "";
        display: inline-block;
        vertical-align: middle;
        width: 16px;
        height: 16px;
        background-image: url("../assets/img/1684984637.png");
        background-size: contain;
        margin-right: 8px;
      }
    }
  }
}
.header {
  width: 100%;
  height: 100px;
  .header-content {
    width: 1200px;
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    .logo {
      width: 380px;
      height: 80px;
      padding-top: 20px;
    }
    .menu {
      margin-top: 20px;
      display: flex;
      a {
        font-size: 16px;
        padding: 0 15px;
        color: #2269a3;
        display: inline-block;
        height: 40px;
        line-height: 40px;
      }
    }
  }
}
.navigation {
  height: 360px;
  width: 1200px;
  background-size: 100% 360px;
  background-image: url("../assets/img/1684984655.jpg");
  display: block;
  margin: 0 auto;
  position: relative;
  .news {
    position: absolute;
    bottom: 0px;
    .news-top {
      .news-top-icon-left {
        width: 50px;
        height: 50px;
        background: url("../assets/img/1684984656.png") no-repeat;
        position: absolute;
        top: -120px;
        left: 60px;
      }
      .news-top-icon-right {
        width: 50px;
        height: 50px;
        background: url("../assets/img/1684984657.png") no-repeat;
        position: absolute;
        top: -120px;
        right: 60px;
      }
    }
    .news-bottom {
      width: 1200px;
      height: 90px;
      background: rgba(0, 0, 0, 0.3);
      .news-bottom-top {
        display: flex;
        flex-direction: row;
        font-size: 15px;
        .news-bottom-top-left {
          width: 120px;
          background: #88c0ee;
          font-size: 18px;
          text-align: center;
          color: #ffffff;
          line-height: 55px;
          position: relative;
          a {
            position: absolute;
            background: url("../assets/img/month_prev.png") no-repeat center;
            top: 50%;
            margin-top: -7px;
            width: 14px;
            height: 14px;
            left: 5px;
          }
        }
        .news-bottom-top-data {
          flex: 1;
          padding: 10px;
          line-height: 30px;
          a {
            color: #fff;
            font-size: 16px;
            font-weight: normal;
          }
        }
        .news-bottom-top-right {
          width: 110px;
          padding: 10px 20px;
          background-color: #88c0ee;
          color: #fff;
          text-align: center;
          height: 35px;
          line-height: 35px;
          bottom: 0px;
        }
      }
      .news-bottom-bottom {
        height: 35px;
        background-color: #88c0ee;
        font-size: 12px;
        // padding: 6px;
        vertical-align: middle;
        ul {
          height: 100%;
          display: flex;
          flex-direction: row;
          li {
            flex: 1;
            display: flex;
            align-items: center;
            justify-content: center;
            span {
              margin: 0 auto;
              color: #666;
              cursor: pointer;
            }
            span:focus {
              color: #9ff5ff;
              outline: none;
            }
          }
        }
      }
    }
  }
}

.main {
  display: flex;
  flex-direction: column;
  width: 1200px;
  margin: 0 auto;
  .main-one {
    padding-bottom: 30px;
    border-bottom: 1px solid #e3e2e2;
    margin-bottom: 10px;
    display: flex;
    flex-direction: row;
    .main-one-left {
      width: 785px;
      padding: 0 30px 0 0;
      .main-one-left-title {
        height: 40px;
        font-size: 22px;
        color: #444444;
        line-height: 40px;
        padding-bottom: 20px;
        span {
          float: right;
        }
        i {
          padding-left: 10px;
          font-size: 22px;
          color: #444444;
          line-height: 40px;
          padding-bottom: 20px;
        }
        img {
          vertical-align: middle;
        }
      }
      .main-one-left-box {
        height: 386px;
        // background: #000;
        .main-one-left-box-top {
          height: 277px;
          ul {
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            li {
              width: 370px;
              img {
                width: 370px;
                height: 210px;
                overflow: hidden;
                cursor: pointer;
                display: block;
              }
              a:nth-of-type(2) {
                display: block;
                border: 1px solid #e3e2e2;
                border-top: none;
                padding: 8px 12px;
                line-height: 22px;
                height: 44px;
                font-size: 16px;
              }
            }
          }
        }
        .main-one-left-box-bottom {
          flex: 1;
          ul {
            li {
              float: left;
              width: 350px;
              margin-right: 20px;
              height: 33px;
              line-height: 25px;
              background: url("../assets/img/icon_dian_2.png") no-repeat left
                11px;
              font-size: 14px;
              padding-left: 20px;
            }
          }
        }
      }
    }
    .main-one-right {
      width: 385px;
      height: 448px;
      display: flex;
      flex-direction: column;
      .main-one-right-top {
        width: 100%;
        height: 170px;
        margin-bottom: 30px;
        .main-one-left-title {
          height: 40px;
          font-size: 22px;
          color: #444444;
          line-height: 40px;
          padding-bottom: 20px;
          span {
            float: right;
          }
          i {
            padding-left: 10px;
            font-size: 22px;
            color: #444444;
            line-height: 40px;
            padding-bottom: 20px;
          }
          img {
            vertical-align: middle;
          }
        }
        .main-one-right-top-content {
          li {
            line-height: 40px;
            height: 40px;
            border-bottom: 1px solid #e7e7e7;
            background: url("../assets/img/icon_dian.png") no-repeat 5px center;
            padding-left: 20px;
          }
          a {
            font-size: 14px;
          }
          span {
            float: right;
            color: #999;
          }
        }
      }
      .main-one-right-bottom {
        height: 256px;
        .main-one-left-title {
          height: 40px;
          font-size: 22px;
          color: #444444;
          line-height: 40px;
          padding-bottom: 20px;
          span {
            float: right;
          }
          i {
            padding-left: 10px;
            font-size: 22px;
            color: #444444;
            line-height: 40px;
            padding-bottom: 20px;
          }
          img {
            vertical-align: middle;
          }
        }
        .main-one-right-content {
          li {
            height: 40px;
            line-height: 20px;
            margin-bottom: 12px;
            font-size: 14px;
            display: flex;
            flex-direction: row-reverse;
            a:active,
            :hover {
              color: #23527c;
            }
            a:active,
            a:hover + span {
              background: #bc3b36;
            }
          }
          span {
            display: block;
            float: left;
            height: 40px;
            line-height: 40px;
            background: #eff1f2;
            text-align: center;
            width: 45px;
            font-size: 12px;
            margin-right: 15px;
            color: #999999;
          }
          span:active,
          span:hover {
            background: #bc3b36;
          }
        }
      }
    }
  }
  .main-two {
    width: 1200px;
    height: 680px;
    margin: 0 auto;
    .main-two-hd {
      height: 80px;
      line-height: 80px;
      padding: 0px 10px 0px 20px;
      position: relative;
      ul {
        float: left;
        position: absolute;
        left: 50%;
        top: 15px;
        height: 40px;
        margin-left: -415px;
        li {
          float: left;
          padding: 0 35px 0 45px;
          cursor: pointer;
          font-size: 22px;
          height: 40px;
          line-height: 40px;
          background: url("../assets/img/tab_icon_01.png") no-repeat left center;
          img {
            vertical-align: middle;
            padding: 0 10px;
          }
          i {
            color: #999999;
            font-size: 14px;
            font-family: Arial;
          }
        }
      }
    }
    .main-two-bd {
      padding: 5px 0;
      height: 590px;
      ul {
        li {
          float: left;

          margin-bottom: 13px;
        }
        img {
          float: left;
          width: 290px;
          height: 165px;
        }
        .txt {
          float: left;
          width: 250px;
          padding: 8px 20px;
          a {
            font-size: 15px;
            line-height: 24px;
            color: #ffffff;
          }
        }
        li:nth-of-type(1) {
          margin-right: 13px;
          width: 897px;
          height: 338px;
          background: #88c0ee;
          img {
            float: left;
            width: 603px;
            height: 338px;
            overflow: hidden;
          }
          .txt {
            float: left;
            width: 254px;
            height: 298px;
            padding: 20px;
            a {
              font-size: 16px;
              line-height: 24px;
              color: #ffffff;
            }
            p {
              text-indent: 2em;
              padding: 20px 0;
              line-height: 30px;
              font-size: 14px;
              color: #ffffff;
            }
            .txt-a {
              display: block;
              text-align: right;
              width: 254px;
              height: 24px;
              position: relative;
              img {
                position: absolute;
                vertical-align: middle;
                right: 0;
                width: 40px;
                height: 8px;
              }
            }
          }
        }
        li:nth-of-type(2) {
          width: 290px;
          height: 338px;
          background: #b4b3f6;
          a:first-child {
            float: left;
            width: 290px;
            height: 165px;
            img {
              width: 290px;
              height: 165px;
            }
          }
          .txt {
            float: left;
            width: 250px;
            height: 157px;
            padding: 10px 20px;
            a {
              width: 240px;
              height: 46px;
              font-size: 16px;
              line-height: 24px;
              color: #ffffff;
            }
            img {
              padding-top: 15px;
              text-align: center;
            }
          }
        }
        li:nth-of-type(3) {
          margin-right: 13px;
          width: 290px;
          height: 230px;
          background: #7bb0dc;
        }
        li:nth-of-type(4) {
          width: 290px;
          margin-right: 13px;
          height: 230px;
          background: #79cac4;
        }
        li:nth-of-type(5) {
          width: 290px;
          height: 230px;
          margin-right: 13px;
          background: #e4bf72;
        }
        li:nth-of-type(6) {
          width: 290px;
          height: 230px;
          background: #88c0ee;
        }
      }
    }
  }
  .main-link {
    background: url("../assets/img/1684984691.png") no-repeat left center;
    height: 100px;
    margin-top: 10px;
    .main-link-scroll {
      width: 1000px;
      position: relative;
      margin-left: 165px;
      .main-link-scroll-hd {
        .next {
          background: url("../assets/img/link_right.png") no-repeat;
          right: -30px;
          top: 30px;
        }
        .prev {
          background: url("../assets/img/link_left.png") no-repeat;
          left: -30px;
          top: 30px;
        }
        .next,
        .prev {
          display: block;
          width: 11px;
          height: 25px;
          position: absolute;
          overflow: hidden;
          cursor: pointer;
        }
      }
      .main-link-scroll-bd {
        .wrap {
          overflow: hidden;
          position: relative;
          width: 999px;
          ul {
            width: 1665px;
            left: 0px;
            position: relative;
            overflow: hidden;
            padding: 0px;
            margin: 0px;
            li {
              float: left;
              width: 65px;
              margin: 0 23px;
              overflow: hidden;
              text-align: center;
              .pic {
                text-align: center;
                padding-top: 5px;
                a {
                  width: 65px;
                  height: 65px;
                  display: block;
                  background: url("../assets/img/1684984694.png") no-repeat;
                }
              }
              .title {
                width: 65px;
                line-height: 24px;
                padding-top: 6px;
              }
            }
          }
        }
      }
    }
  }
  /* 自适应主要内容区域高度 */
}

.footer {
  background: url("../assets/img/1684984709.png") no-repeat top center;
  height: 280px;
  width: 100%;
  margin: 30px auto 0;
  .footer-top,
  .footer-mid,
  .footer-bottom {
    width: 1200px;
    margin: 0 auto;
  }
  .footer-top {
    display: flex;
    flex-direction: row;
    margin: 0 auto;
    // justify-content: space-between;
    .footer-top-left {
      background: url("../assets/img/tit_link.png") no-repeat left center;
      padding-left: 120px;
      height: 82px;
      width: 700px;
      display: flex;
      align-items: center;
      a {
        padding-right: 15px;
        line-height: 30px;
        color: #ffffff;
        font-size: 13px;
      }
    }
    .footer-top-right {
      display: flex;
      width: 370px;
      ul {
        display: flex;
        align-items: center;

        flex-direction: row;
        font-size: 14px;
        li {
          margin-left: 22px;
          color: #ffffff;
          position: relative;
        }
      }
    }
  }
  .footer-mid {
    height: 200px;
    margin: 0 auto;
    display: flex;
    .footer-mid-logo {
      width: 220px;
      padding: 30px 20px 40px 50px;
      margin: 20px 0 60px 0;
      border-right: 1px solid #d2e7f8;
    }
    .footer-mid-data {
      width: 400px;
      color: #ffffff;
      font-size: 13px;
      flex: 1;
      margin: 20px 0 0 30px;
      p {
        color: #ffffff;
        line-height: 22px;
      }
    }
    .footer-mid-qr {
      width: 300px;
      margin-left: auto;
      margin-top: 20px;
      display: flex;
      flex-direction: row;
      span {
        display: flex;
        flex-direction: column;
        text-align: center;
        padding: 0 20px;
        color: #ffffff;
      }
    }
  }
  .footer-bottom {
    line-height: 50px;
    text-align: center;
    font-size: 13px;
    color: #a4a4a4;
    display: flex;
    flex-direction: row;
    justify-content: center;
    position: relative;

    .back {
      position: absolute;
      width: 110px;
      // height: 36px;
      right: 0px;
      bottom: 0px;
      display: flex;
      a {
        color: #a4a4a4;
        cursor: pointer;
        display: inline;
        img {
          margin-left: 6px;
        }
      }
      a:active,
      :hover {
        color: #23527c;
      }
    }
  }
}
</style>