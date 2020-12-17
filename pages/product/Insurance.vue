<template>
  <div id="pointsBenefit">
    <div class="banner">
      <img src="../../assets/img/product/商保/组 1352@2x.png" alt="" />
    </div>

    <!-- 企业补充医疗保险有何价值 -->
    <div class="block block2 block3 anyValueBox">
      <p class="block-title">企业补充医疗保险有何价值</p>
      <div class="bgico"></div>
      <div class="innerBlock" style="margin-top: 0">
        <div class="imgwarp">
          <img src="../../assets/img/product/商保/组 1454@2x.png" alt="" />
        </div>
        <div class="info">
          <ul>
            <li>
              <img src="../../assets/img/product/商保/组 1544@2x.png" alt="" />
              <span>丰富企业福利内容，最大化满足员工保障需求</span>
            </li>
            <li>
              <img src="../../assets/img/product/商保/组 1545@2x.png" alt="" />
              <span>最有温度的员工福利，提高员工归属感和感知度</span>
            </li>
            <li>
              <img src="../../assets/img/product/商保/组 1546@2x.png" alt="" />
              <span>构建企业健康保障体系，有效管控企业医疗成本</span>
            </li>
          </ul>
        </div>
      </div>
      <div class="btnGroup">
        <div class="btn" @click="$router.push('/fillinginfo')">
          获取解决方案
        </div>
        <div class="showBtn" @click="$router.push('/fillinginfo')">
          立刻参保
        </div>
      </div>
    </div>

    <!-- 企业难点 -->
    <div class="block block1">
      <p class="block-title">企业实行补充医疗保险的难点</p>
      <div class="bgico"></div>
      <ul>
        <li>
          <div class="warpImg">
            <img src="../../assets/img/product/商保/蒙版组 11@2x.png" />
          </div>
          <p>
            企业实行补充医疗保险的难点<span class="highlightText"
              >选择困难</span
            >
          </p>
        </li>
        <li>
          <div class="warpImg">
            <img src="../../assets/img/product/商保/蒙版组 12@2x.png" />
          </div>
          <p>
            与保险机构对接麻烦，<span class="highlightText">理赔流程复杂</span>
          </p>
        </li>
        <li>
          <div class="warpImg">
            <img src="../../assets/img/product/商保/组 1468@2x.png" />
          </div>
          <p>
            花费大量时间选品、采购、寄送，专人负责福利管理，<span
              class="highlightText"
              >耗时耗力</span
            >
          </p>
        </li>
      </ul>

      <div class="btn morePlan" @click="$router.push('/fillinginfo')">
        获取服务方案
      </div>
    </div>

    <!-- 泛员网企业补充医疗保险方案介绍 -->
    <div class="block block2 Introduce">
      <p class="block-title">泛员网企业补充医疗保险方案介绍</p>
      <div class="bgico"></div>
      <div class="innerBlock" style="max-width: 1375px">
        <div class="info">
          <h4>7类保险套餐，满足多样化需求</h4>
          <ul>
            <li>
              12年企业商保服务经验，甄选最适合企业的<span class="highlightText"
                >保险套餐</span
              >，每类套餐有<span class="highlightText">多种保额项目</span
              >可供选择。
            </li>
            <li>
              <span class="highlightText">泛员温度价最低10元/人/月。</span>
            </li>
          </ul>
          <div class="btn" @click="$router.push('/fillinginfo')">预约体验</div>
        </div>
        <div class="SwiperOptionsIntroduce">
          <swiper :options="SwiperOptionsIntroduce">
            <swiper-slide>
              <img src="../../assets/img/product/商保/组 1577@2x.png" />
            </swiper-slide>
            <swiper-slide>
              <img src="../../assets/img/product/商保/组 1578@2x.png" />
            </swiper-slide>
            <swiper-slide> 
              <img src="../../assets/img/product/商保/组 1579@2x.png" />
            </swiper-slide>
            <swiper-slide> 
              <img src="../../assets/img/product/商保/组 1580@2x.png" />
            </swiper-slide>
          </swiper>
          <div class="swiper-pagination pagination"></div>
        </div>
      </div>
    </div>
    <div class="block block2 block3" style="padding: 0px 0 56px">
      <div class="innerBlock">
        <div class="imgwarp">
          <img
            style="max-width: 987px; min-width: 800px"
            src="../../assets/img/product/商保/组 1530@2x.png"
            alt=""
          />
        </div>
        <div class="info">
          <h4>随时在线参缴、理赔与停保</h4>
          <ul>
            <li>企业可以在线选择配置适合的保险套餐</li>
            <li>随时为员工<span class="highlightText">在线参缴与停保</span></li>
            <li>
              随时查看<span class="highlightText">套餐状态与汇总数据</span>
            </li>
          </ul>
          <div class="btn" @click="$router.push('/fillinginfo')">预约体验</div>
        </div>
      </div>
    </div>
    <!-- 结算方式 -->
    <div class="block block2" style="padding-bottom: 70px">
      <div class="innerBlock" style="max-width: 1289px">
        <div class="info" style="width: 423px">
          <h4 style="margin-bottom: 0; flex: none">按月付费，灵活结算</h4>
          <ul>
            <li>
              <span class="highlightText"
                >系统自动生成月度账单，按月结算付费</span
              >
            </li>
            <li>
              相比保险公司，合作前期企业可<span class="highlightText"
                >节省更多现金流</span
              >。
            </li>
          </ul>
          <div class="btn" @click="$router.push('/fillinginfo')">预约体验</div>
        </div>
        <div class="imgwarp">
          <img
            style="max-width: 773px"
            src="../../assets/img/product/商保/组 1529@2x.png"
            alt=""
          />
        </div>
      </div>
    </div>
    <!-- 理赔响应 -->
    <div class="block block2 block3" style="padding: 0px 0 56px">
      <div class="innerBlock">
        <div class="imgwarp">
          <img
            style="max-width: 857px; min-width: 800px"
            src="../../assets/img/product/商保/组 1527@2x.png"
            alt=""
          />
        </div>
        <div class="info">
          <h4>员工线上理赔，客服中心及时响应</h4>
          <ul>
            <li>
              员工直接通过泛员网客服中心发起<span class="highlightText"
                >在线理赔。</span
              >
            </li>
            <li>
              专属客户经理及在线客户<span class="highlightText">及时响应</span
              >企业及员工咨询和服务反馈。
            </li>
          </ul>
          <div class="btn" @click="$router.push('/fillinginfo')">预约体验</div>
        </div>
      </div>
    </div>

    <!-- 泛员网带来的价值 -->
    <div class="block block1 valueBox">
      <p class="block-title">泛员网带来的价值</p>
      <div class="bgico"></div>
      <ul>
        <li>
          <div class="warpImg">
            <img src="../../assets/img/product/商保/组 1499@2x.png" />
          </div>
          <p>
            12年企业商保服务，深刻洞悉企业及员工需求，精选最合适的保险套餐，<span
              class="highlightText"
              >HR不再“选择困难”</span
            >
          </p>
        </li>
        <li>
          <div class="warpImg">
            <img src="../../assets/img/product/商保/组 1504@2x.png" />
          </div>
          <p>
            <span class="highlightText">直接与泛员网对接，</span><br />
            省去与保险机构的复杂对接流程
          </p>
        </li>
        <li>
          <div class="warpImg">
            <img src="../../assets/img/product/商保/组 1522@2x.png" />
          </div>
          <p>
            多渠道处理员工咨询及服务反馈，<br /><span class="highlightText"
              >员工更满意</span
            >
          </p>
        </li>
        <li>
          <div class="warpImg">
            <img src="../../assets/img/product/商保/组 1516@2x.png" />
          </div>
          <p>
            灵活的在线参缴与停保，随时查看汇总数据，<span class="highlightText"
              >企业操作管理更便捷</span
            >
          </p>
        </li>
      </ul>
      <div class="btn" @click="$router.push('/fillinginfo')">预约体验</div>
    </div>

    <div class="block block1 flow">
      <p class="block-title">3大实施流程，轻松落地服务方案</p>
      <div class="bgico"></div>
      <div class="info flowInfo">
        <img src="../../assets/img/product/商保/组 1418@2x.png" alt="" />
      </div>
      <div class="btn" @click="$router.push('/fillinginfo')">预约体验</div>
    </div>
    <!-- 给员工一份最有温度的福利保障吧~ -->
    <div class="block block1 flow giveSafeguard">
      <p class="block-title">给员工一份最有温度的福利保障吧</p>
      <div class="bgico"></div>
      <div class="info">
        <!-- 表单填写 -->
        <ul>
          <li>
            <img src="../../assets/img/product/商保/姓名@2x.png" alt="" />
            <input type="text" placeholder="您的称呼" />
          </li>
          <li>
            <img src="../../assets/img/product/商保/手机@2x.png" alt="" />
            <input type="text" placeholder="您的联系方式" />
          </li>
        </ul>
        <ul>
          <li>
            <img src="../../assets/img/product/商保/企业@2x.png" alt="" />
            <input type="text" placeholder="您的公司名称" />
          </li>
          <li>
            <img src="../../assets/img/product/商保/蒙版组 18@2x.png" alt="" />
            <input type="text" placeholder="投保人数" />
          </li>
        </ul>
        <ul>
          <li id="safeguardProject">
            <img src="../../assets/img/product/商保/规模指标@2x.png" alt="" />
            <input type="text" placeholder="您需要为员工保障的项目" />
          </li>
        </ul>
      </div>
      <div class="btn" @click="$router.push('/fillinginfo')">立刻参保</div>
      <div class="moreScheme">
        <span>更多员工福利保障方案，欢迎咨询</span>
        <div class="showBtn">在线客服</div>
      </div>
    </div>
    <!-- 500+企业 -->
    <div class="block casus">
      <p class="block-title">500+大中型企业信赖的选择</p>
      <div class="bgico"></div>
      <ul>
        <li>
          <div class="imgWarp">
            <img src="../../assets/img/product/商保/蒙版组 5@2x.png" alt="" />
          </div>
          <div class="title">
            <div class="ico">物流</div>
            <h4>某物流公司</h4>
          </div>
          <div class="content">
            <h3>员工补充医疗保险实施案例</h3>
            <div class="label">
              <span class="orangeLabel">物流/运输</span>
              <span class="blueLabel">补充医疗保险/交通差旅险</span>
            </div>
            <p>
              该公司员工常年奔波在路上运输货物，用车较多，通过泛员网为员工配置了交通差旅保险，加强了企业差旅风险防范能力，也增强了员工的福利感知度。
            </p>
          </div>
        </li>
        <li>
          <div class="imgWarp">
            <img src="../../assets/img/product/商保/蒙版组 6@2x.png" alt="" />
          </div>
          <div class="title">
            <div class="ico">建筑</div>
            <h4>中国某建筑集团公司</h4>
          </div>
          <div class="content">
            <h3>员工补充医疗保险实施案例</h3>
            <div class="label">
              <span class="orangeLabel">建筑/央企</span>
              <span class="blueLabel">补充医疗保险</span>
            </div>
            <p>
              该集团全年有上百个工程项目在开工，为提高员工的安全保障，配置了意外保险套餐，工伤赔付支出降低了85%，有效地减少了公司成本。
            </p>
          </div>
        </li>
        <li>
          <div class="imgWarp">
            <img src="../../assets/img/product/商保/蒙版组 7@2x.png" alt="" />
          </div>
          <div class="title">
            <div class="ico" style="font-size: 16px">投行</div>
            <h4>某投资银行</h4>
          </div>
          <div class="content">
            <h3>员工补充医疗保险实施案例</h3>
            <div class="label">
              <span class="orangeLabel">金融/投资</span>
              <span class="blueLabel">补充医疗保险</span>
            </div>
            <p>
              该行员工业务繁忙，业绩压力较大，银行平时注重企业的福利管理，为员工和高管分别配置了医疗保障和豪华医疗套餐，极大地提升了员工的满意度。
            </p>
          </div>
        </li>
      </ul>
      <div class="btnGroup">
        <!-- <div class="moreBtn">查看更多行业案例</div> -->
        <div class="showBtn" @click="$router.push('/fillinginfo')">
          预约体验
        </div>
      </div>
    </div>
    <!-- 常见问题 -->
    <div class="block block1 flow" id="qa">
      <p class="block-title">给员工一份最有温度的福利保障吧</p>
      <div class="bgico"></div>
      <div class="info">
        <client-only>
          <swiper :options="indexSwiperOptions">
            <swiper-slide class="indexSwiperBox1">
              <ul>
                <li>
                  <div class="head">
                    <img
                      src="../../assets/img/product/商保/组 1482@2x.png"
                      alt=""
                    />
                    <p>
                      进行投保停保申报时，是否可以往前追溯，报今天之前的时间？
                    </p>
                  </div>
                  <div class="content">
                    不可往前追溯，最早的生效时间只能填写申报的第二天。可当天投，次日停。
                  </div>
                </li>
                <li>
                  <div class="head">
                    <img
                      src="../../assets/img/product/商保/组 1482@2x.png"
                      alt=""
                    />
                    <p>商保套餐与社保的工伤保险有什么本质区别？</p>
                  </div>
                  <div class="content">
                    工伤是承认发生的工作时间内的伤害，商保是提供7*24小时的保障。
                  </div>
                </li>
                <li>
                  <div class="head">
                    <img
                      src="../../assets/img/product/商保/组 1482@2x.png"
                      alt=""
                    />
                    <p>
                      客户同一个人购买了2份保险套餐，理赔时是否可以领取2份保险金？
                    </p>
                  </div>
                  <div class="content">
                    重大疾病、疾病身故、意外伤残、意外身故，都属于一次性给付型险种，可以叠加给付；<br />
                    意外医疗、意外住院津贴、补充门诊医疗、补充住院医疗、生育保险，属于医疗报销型险种，赔付金额不能多于实际支付金额。即，可以叠加，但需根据实际的发票来报销的，报销过了就不能重复报销。
                  </div>
                </li>
              </ul>
              <ul>
                <li>
                  <div class="head">
                    <img
                      src="../../assets/img/product/商保/组 1482@2x.png"
                      alt=""
                    />
                    <p>关于投保人有无社保，有什么具体的影响？</p>
                  </div>
                  <div class="content">
                    只会影响包含“补充住院医疗”“生育报销”的保险套餐的理赔，有无社保的报销比例会不一样。
                  </div>
                </li>
                <li>
                  <div class="head">
                    <img
                      src="../../assets/img/product/商保/组 1482@2x.png"
                      alt=""
                    />
                    <p>理赔期间是否需要续保？</p>
                  </div>
                  <div class="content">
                    长期的：如生育、住院，需要保持续保状态。<br />
                    短期的：不用续保。但期间离职了，则无法报销。
                  </div>
                </li>
                <li>
                  <div class="head">
                    <img
                      src="../../assets/img/product/商保/组 1482@2x.png"
                      alt=""
                    />
                    <p>员工已经有社保了，再买这个会不会浪费？</p>
                  </div>
                  <div class="content">
                    补充医疗保险提供因意外事故造成意外伤害给付身故、伤残以及意外医疗保险金，并有意外住院津贴，还提供电话医疗咨询服务及意外住院医疗费用垫付服务，是社保的极好补充，是企业为员工提供的最有温度的健康福利。
                  </div>
                </li>
              </ul>
            </swiper-slide>
            <swiper-slide class="indexSwiperBox2"> 
              <ul>
                <li>
                  <div class="head">
                    <img
                      src="../../assets/img/product/商保/组 1482@2x.png"
                      alt=""
                    />
                    <p>报销型的险种，分别按规则报销？该怎么用？</p>
                  </div>
                  <div class="content">
                    <p>△重大前提：凡报销，商保报销部分不能与社保报重复；即，商保报销的是社保报销完后的剩余部分。</p>
                    <p>△意外身故及伤残、重大疾病、疾病身故，属于“一次性赔付”，不存在报销比例的说法。</p>
                    <p>1、意外医疗：包括意外门诊和意外住院</p>
                    <p>意外导致门诊：有无社保都按照方案赔付比例赔付（如报销社保范围内的医疗用药，且0元免赔额，100%赔付）</p>
                    <p>意外导致住院：有社保必须先报社保，剩余部分100%报销（合理医疗范围），无社保报销50%（合理医疗范围）。</p>
                    <p>2、意外住院津贴：因意外导致的住院，可以申请意外医疗，同时申请意外住院津贴。</p>
                    <p>3、补充住院医疗：有社保必须先报社保，剩余部分100%报销（合理医疗范围），无社保报销50%（合理医疗范围）。</p>
                    <p>4、补充门诊医疗：只报社保范围内的医疗用药。意义在于替代社保卡的门诊检查、买药。注意：补充门诊与补充住院，共享上限额度。</p>
                    <p>5、生育保险：</p>
                    <p>（1）保障包括生育检查/分娩等生育医疗费用。</p>
                    <p>（2）投保时有无怀孕：有怀孕，且怀孕前未在任何保险公司买过生育险，则本次怀孕不能理赔。</p>
                    <p>有怀孕，且在之前有买过的生育险，并在保单失效前就已怀孕，则可以赔付本次投保之后发生的生育医疗费用。（与保险公司无关，两次投保可在不同保险公司，且中间可以有空档期。）</p>
                    <p>无怀孕，则正常享受保障范围。</p>
                    <p>（3）有社保必须先报社保，扣除社保统筹后的剩余部分100%报销，无社保报销50%。</p>
                  </div>
                </li>
              </ul>
            </swiper-slide>
          </swiper>
          <div class="swiper-pagination pagination"></div>
        </client-only>
      </div>
      <div class="btn" @click="$router.push('/fillinginfo')">在线咨询</div>
    </div>
    <div class="footer">
      <div class="iconList">
        <ul>
          <li>
            <img
              src="../../assets/img/product/积分福利/publicity/组 1426@2x.png"
              alt=""
            />
            <p>HCM SaaS</p>
          </li>
          <li>
            <img
              src="../../assets/img/product/积分福利/publicity/组 1427@2x.png"
              alt=""
            />
            <p>全国社保外包</p>
          </li>
          <li>
            <img
              src="../../assets/img/product/积分福利/publicity/组 1428@2x.png"
              alt=""
            />
            <p>薪酬服务外包</p>
          </li>
          <li>
            <img
              src="../../assets/img/product/积分福利/publicity/组 1429@2x.png"
              alt=""
            />
            <p>积分福利</p>
          </li>
        </ul>
        <ul>
          <li>
            <img
              src="../../assets/img/product/积分福利/publicity/组 1425@2x.png"
              alt=""
            />
            <p>节日福利</p>
          </li>
          <li>
            <img
              src="../../assets/img/product/积分福利/publicity/组 1424@2x.png"
              alt=""
            />
            <p>补充保险</p>
          </li>
          <li>
            <img
              src="../../assets/img/product/积分福利/publicity/组 1423@2x.png"
              alt=""
            />
            <p>年度体检</p>
          </li>
        </ul>
      </div>
      <div class="content">
        <p class="change">选择泛员网 拥抱数字化</p>
        <h2>持续提升人力资源运营效能</h2>
        <p class="desc">一个平台，处理大中型企业更多HR管理与服务需求…</p>
        <div class="warpBtn">
          <div class="btnWhite" @click="$router.push('/fillinginfo')">
            预约体验
          </div>
          <div class="btnLine" @click="MoNiClick">预约体验</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: "fyw",
  head() {
    return {
      title: "员工福利_弹性福利平台_企业福利积分商城_薪酬福利",
      meta: [
        {
          hid: "keywords",
          name: "keywords",
          content:
            "积分商城，员工福利，薪酬福利，企业福利平台，弹性福利，弹性福利平台，企业成本管理，降低企业成本，员工收入，员工需求，税务优化",
        },
        {
          hid: "description",
          name: "description",
          content:
            "泛员网积分福利平台整合优质供应商资源，涵盖丰富多样的福利内容，为客户提供一站式企业福利解决方案。合理帮助企业降低成本，为员工降低个税，满足员工个性化需求，帮助企业提升员工满意度和福利感知度，激活组织活力。",
        },
      ],
      
    };
  },
  components: {},
  data() {
    return {
      indexSwiperOptions: {
        autoplay: {
          delay: 50000,
          stopOnLastSlide: false,
          disableOnInteraction: false,
        },
        loop: true,
        pagination: {
          el: '.swiper-pagination',
        },
      },
      SwiperOptionsIntroduce:{
        autoplay: {
          delay: 50000,
          stopOnLastSlide: false,
          disableOnInteraction: false,
        },
        loop: true,
        pagination: {
          el: '.swiper-pagination',
        },
      }
    };
  },
  methods: {
    MoNiClick() {
      document.getElementById("kf5-support-btn").click();
    },
  },
};
</script>
<style>
#pointsBenefit .pagination{
  transform:translate(-50%,-50%);
  left: 50%;
  bottom: -26px;
}
#pointsBenefit .pagination span{
  display: inline-block;
  margin-right: 12px;
}
#pointsBenefit .swiper-pagination-bullet{
  height: 12px;
  width: 12px;
  background: none;
  border: 2px solid #A6C0FC;
}
#pointsBenefit .swiper-pagination-bullet-active{
  background: #A6C0FC!important;
  width: 36px;
  height: 12px;
  border-radius: 6px;
}
#pointsBenefit .Introduce .swiper-pagination-bullet-active{
  background: #A6C0FC!important;
  width: 24px;
  height: 10px;
  border-radius: 6px;
}

#pageContainer{
  padding-bottom: 0!important;
}
</style>
<style scoped>
@import "../../assets/product_public.css";
.footer {
  position: relative;
  height: 500px;
  background-size: 150%;
  background: url("../../assets/img/product/积分福利/publicity//组 1430.png");
  display: flex;
  color: #fff;
  justify-content: center;
  padding-top: 100px;
  /* align-items: center; */
  box-sizing: border-box;
}
.footer .change {
  color: #58fecb;
  font-size: 24px;
}
.footer h2 {
  font-size: 36px;
  margin-top: 16px;
}
.footer .desc {
  font-size: 20px;
  margin-top: 16px;
}
.info li {
  width: 418px !important;
}
.footer .warpBtn {
  display: flex;
  margin-top: 70px;
}
.footer .btnWhite {
  width: 180px;
  text-align: center;
  line-height: 50px;
  height: 50px;
  color: #4c80fa;
  font-size: 20px;
  background: #ffffff;
  border-radius: 25px;
  box-shadow: 0px 10px 20px 0px rgba(12, 53, 149, 0.4);
  user-select: none;
  cursor: pointer;
  margin-right: 30px;
}
.footer .btnLine {
  user-select: none;
  cursor: pointer;
  width: 160px;
  height: 50px;
  line-height: 46px;
  border: 2px solid #ffffff;
  font-size: 20px;
  font-family: Source Han Sans SC, Source Han Sans SC-Regular;
  font-weight: 400;
  text-align: center;
  color: #ffffff;
  border-radius: 25px;
}
.iconList {
  width: 532px;
  margin: 20px 60px;
}
.footer .content {
  width: 500px;
}
.iconList ul {
  display: flex;
  justify-content: space-around;
}
.iconList ul li {
  list-style: none;
  margin-bottom: 35px;
}
.iconList ul li:last-child {
  margin-bottom: 0;
}
.iconList img {
  width: 70px;
  margin-bottom: 8px;
}
.giveSafeguard {
  background: #f7f8fd;
}
.giveSafeguard .flowInfo {
  display: block;
}

.giveSafeguard .info ul {
  width: 830px;
}
.giveSafeguard .info li {
  display: flex;
  flex-direction: row;
  border: 1px solid #e5e5e5;
  background: #fff;
  padding: 15px 20px;
  width: 400px !important;
  box-sizing: border-box;
}
.giveSafeguard .info li img {
  width: 20px;
  margin-bottom: 0;
  margin-right: 15px;
}
.giveSafeguard .info li input {
  border: none;
  width: 300px;
}
#safeguardProject {
  width: 830px !important;
}
.moreScheme {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 50px;
}
.moreScheme span {
  margin-right: 20px;
}
.moreScheme .showBtn {
  height: 38px;
  line-height: 38px;
  width: 132px;
}
.valueBox {
  background: #f7f8fd;
}
.valueBox .warpImg {
  width: 172px;
  height: 176px;
}
.valueBox li p {
  width: 268px;
}
.valueBox .warpImg img {
  width: 100%;
}
.valueBox .btn {
  margin: 20px auto 0;
}
.valueBox ul {
  width: 1230px;
}

.casus {
  padding-top: 87px;
}
.casus ul {
  display: flex;
  width: 1234px;
  margin: 0 auto;
  justify-content: space-between;
}
.casus ul li {
  width: 398px;
  border: 1px solid #e1e1e2;
  border-radius: 10px 10px 0 0;
  flex: none;
  list-style: none;
}
.casus ul li img {
  width: 100%;
}
.casus .ico {
  border-radius: 50%;
  background: #fff;
  width: 61px;
  height: 61px;
  box-shadow: 0px 3px 6px 0px rgba(0, 0, 0, 0.16);
  text-align: center;
  line-height: 61px;
  font-size: 16px;
  position: relative;
  top: -36px;
  margin-right: 10px;
  color: #747784;
}
.casus .title {
  display: flex;
  padding-left: 18px;
  margin-top: 5px;
  margin-bottom: -12px;
}
.casus .title h4 {
  color: #38424f;
  margin-left: 10px;
}
.casus .content {
  padding: 0 16px 16px;
}
.casus .content h3 {
  font-size: 20px;
  margin-bottom: 15px;
}
.casus .content p {
  text-align: justify;
  padding-top: 26px;
  color: #747784;
  font-size: 16px;
}
/* .casus .label span{
  display: inline-block;
  background: #fff;
  text-align: center;
  line-height: 24px;
  padding: 0 10px;
  color: #4C80FA;
  font-size: 12px;
  height: 24px;
  margin-right: 10px;
  border-radius: 12px;
  box-shadow: 2px 2px 4px 0px rgba(12,53,149,0.1); 
} */
.orangeLabel {
  height: 28px;
  padding: 0 10px;
  line-height: 28px;
  background: #fff6eb;
  border: 1px solid #ff8a00;
  border-radius: 4px;
  display: inline-block;
  text-align: center;
  color: #ff8a00;
  margin-right: 10px;
}
.blueLabel {
  color: #4c80fa;
  height: 28px;
  padding: 0 10px;
  line-height: 28px;
  background: #f5f9ff;
  border: 1px solid #4c80fa;
  border-radius: 4px;
  display: inline-block;
  text-align: center;
}

.highlightText {
  color: #ff7300;
  font-size: 16px;
}
.btnGroup {
  display: flex;
  justify-content: center;
  margin: 10px 0 68px;
}
.moreBtn {
  width: 220px;
  height: 50px;
  line-height: 50px;
  text-align: center;
  border: 1px solid #4c80fa;
  border-radius: 25px;
  color: #4c80fa;
  font-size: 16px;
  margin-right: 30px;
  cursor: pointer;
  user-select: none;
}
.showBtn {
  width: 160px;
  height: 50px;
  line-height: 50px;
  color: #ff7300;
  font-size: 16px;
  text-align: center;
  border: 1px solid #ff7300;
  border-radius: 25px;
  cursor: pointer;
  user-select: none;
}
#pointsBenefit .banner {
  /* height: 500px; */
  /* background: url("../../assets/img/product/积分福利/publicity/banner.png"); */
  /* background-size: cover; */
  width: 100%;
}
#pointsBenefit .banner img {
  width: 100%;
}
.morePlan {
  margin: 40px auto 0;
  width: 220px !important;
}
.btn {
  width: 166px;
  height: 50px;
  background: linear-gradient(69deg, #ff7600 0%, #ff9700 100%);
  box-shadow: 0px 5px 5px 0px rgba(56, 49, 35, 0.23);
  border-radius: 25px;
  text-align: center;
  line-height: 50px;
  font-size: 14px;
  font-weight: 400;
  color: #ffffff;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  cursor: pointer;
}
.block .block-title {
  font-size: 40px;
  margin-bottom: 20px;
}
.block li img {
  width: 64px;
}
.block li p {
  color: #222531;
  text-align: center;
}
.block li {
  width: 302px;
  margin-bottom: 38px;
  font-size: 16px;
}
.flow img {
  width: 100%;
}
.flow .btn {
  margin: 50px auto 0;
}
.flowInfo {
  overflow: hidden;
  width: 100%;
  position: relative;
  display: flex;
  justify-content: center;
}
.flowInfo img {
  width: 100%;
}
@media screen and (max-width: 1500px) {
  .flowInfo img {
    width: 125%;
  }
}
.block2 {
  background: #f7f8fd;
  padding-top: 45px;
}
.block2 .innerBlock {
  width: 80%;
  margin-bottom: 0;
}
.block2 .info {
  flex: 1;
}
.block2 .imgwarp img {
  max-width: 904px;
  width: 100%;
}
.block3 .imgwarp img {
  /* width: 987px; */
  width: 100%;
  margin-right: 58px;
}
.block2 .innerBlock {
  /* width: 1380px; */
  width: 80%;
}
.block2 h4 {
  font-size: 20px;
  margin-bottom: 40px;
}
.block3 {
  background: #fff;
  padding-bottom: 0;
}
/* .block3 .innerBlock{
  margin-top: 0;
} */
.warpImg {
  height: 70px;
  margin-bottom: 30px;
}
.innerBlock {
  width: 1160px;
  position: relative;
  justify-content: center;
}
.innerBlock.b1 .desc {
  width: 440px;
  text-align: right;
  position: absolute;
  bottom: 68px;
  margin: 0;
  left: 256px;
}
.innerBlock.b2 .desc {
  width: 360px;
  margin-right: 0;
  margin-left: 20px;
}
.innerBlock.b3 .desc {
  width: 289px;
  margin-right: 55px;
  text-align: right;
}
.bgico {
  margin: 0 auto 55px;
  width: 76px;
  height: 9px;
  background-image: url("../../assets/img/product/积分福利/publicity/重复网格 3@2x.png");
}
.anyValueBox .btnGroup {
  margin-top: 50px;
}
.anyValueBox .imgwarp img {
  width: 90%;
}
.anyValueBox li img {
  width: 60px;
  margin-right: 15px;
}
.anyValueBox li {
  display: flex;
  list-style: none;
  align-items: center;
}
.anyValueBox .btn {
  margin-right: 40px;
}
/* 问答 */
#qa {
  background: #F7F8FD;
  text-align: left;
}
#qa .head {
  display: flex;
  align-items: center;
}
#qa .head p {
  text-align: left;
  color: #222531;
  font-size: 18px;
}
#qa img {
  width: 46px;
  margin-right: 16px;
}
#qa .content {
  background: #ffffff;
  border-radius: 10px;
  padding: 30px;
  width: 520px;
  box-sizing: border-box;
  box-shadow: 0px 10px 10px 0px rgba(76, 128, 250, 0.08);
  margin-top: 20px;
}
#qa .info {
  display: flex;
  width: 1180px;
  margin: 0 auto;
  position: relative;
}
#qa .info ul {
  display: block;
}
#qa .info ul li {
  width: 520px !important;
  align-items: flex-start;
}
.indexSwiperBox1,.indexSwiperBox2{
  display: flex;
  padding-left: 10px;
}
#qa .indexSwiperBox2 p{
  text-align: left;
  margin-bottom: 9px;
}
#qa .indexSwiperBox2 .content{
  width: 1020px;
}
.SwiperOptionsIntroduce{
  max-width: 680px;
  position: relative;
}
.SwiperOptionsIntroduce img{
  width: 680px;
}
.Introduce {
  padding-bottom: 30px;
}
.Introduce .info{
  width: 440px;
  flex: none;
}
.Introduce .pagination{
  bottom: -8px;
}
</style>