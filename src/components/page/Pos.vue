<<template>
    <div class="pos">
        <el-row>
            <el-col :span="7">
                我是订单
            </el-col>
            <el-col>
                我是产品
            </el-col>
        </el-row>
    </div>
</template>
<script>
export default {
  name: 'Pos',
  mounted: function () {
    var orderHeight = document.body.clientHeight
    document.getElementById('order-list').style.height = orderHeight + 'px'
  }
}
</script>
<style scoped>
.pos{
    font-size: 48px;
}
</style>

