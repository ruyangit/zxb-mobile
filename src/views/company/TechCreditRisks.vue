<template>
    <!--信用风险管理-->
    <div class="item xyfxgl active">
        <div class="banner"></div>
        <div class="txt-content">
            <p class="txt-p">凭借信用风险管理方面的专业知识与丰富经验，结合国内外金融机构的最佳实践，帮助企业建立或优化其信用风险管理体系，以支持企业更好地完成授信审批和应收账款管理等。信用风险管理咨询服务涵盖了小额贷款公司、网络金融平台、汽车金融公司、消费金融公司等金融或类金融机构的全信用周期，包括贷前的授信审批，贷中的账户管理以及对逾期账户的催收管理。
            </p>
            <h4>信用风险管理咨询服务可以帮助您</h4>
            <p>1）优化审批流程，提高审批效率</p>
            <p>2）设置差异化的风险定价与合理的额度策略，提高收益率</p>
            <p>3）建立风险预警制度，帮助企业识别潜在风险</p>
            <p>4）完善客户忠诚度管理，提升客户体验与客户忠诚度</p>
            <p>5）差异化的催收策略，降低催收成本</p>
            <p class="fs28 mt30">服务热线：<a class="a-tel" href="tel:400-700-8808">400-700-8808</a></p>
        </div>
        <div class="btn-box">
            <a class="btn" href="javascript:;" @click="myModel=true">我要申请</a>
        </div>
        <CompanyTechBox v-model="myModel" title="信用风险管理" moduleType="2204"></CompanyTechBox>
    </div>
</template>

<script>
import CompanyTechBox from '@/components/CompanyTechBox'
export default {
    data() {
        return {
            myModel: false
        }
    },
    components:{
        CompanyTechBox
    }
}
</script>>
<style scoped>
.xing-box .xyfxgl .banner {
    width: 7.5rem;
    height: 2.1rem;
    background: url(/static/images/company_finance_banner04.png) no-repeat center center;
    background-size: 7.5rem 2.1rem;
}
</style>
