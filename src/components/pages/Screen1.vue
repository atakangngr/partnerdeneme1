<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="0"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="auto" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="33f86120-8ad9-49c1-b308-af8193e314eb" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'4500px','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WAspect
        src="https://quotefancy.com/media/wallpaper/800x450/1471043-Kapil-Dev-Quote-When-you-have-to-work-work-with-a-smile.jpg"
        tag="div" aspect="16:9"
        v-bind:aspects="[{'text':'4:3 (SD)','value':'4:3'},{'text':'1:1 (Square)','value':'1:1'},{'text':'16:9 (HD)','value':'16:9'},{'text':'1.85:1 (Widescreen)','value':'1.85:1'},{'text':'2:1 (Univisium/Superscope)','value':'2:1'},{'text':'21:9 (Anamorphic)','value':'21:9'},{'text':'1.43:1 (IMAX)','value':'1.43:1'},{'text':'3:2 (35mm Film)','value':'3:2'},{'text':'3:1 (APS-P)','value':'3:1'},{'text':'4/3 (Same as 4:3)','value':'4/3'},{'text':'16/9 (Same as 16:9)','value':'16/9'},{'text':'3 (Same as 3:1)','value':'3'},{'text':'2 (Same as 2:1)','value':'2'},{'text':'1.85 (Same as 1.85:1)','value':'1.85'},{'text':'1.5','value':'1.5'},{'text':'1 (Same as 1:1)','value':'1'}]"
        cardText="" bgVariant=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'src','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'CardText'}]}"
        v-bind:textVisibility="true" position="absolute" top="5.207325029203476%" left="22.852658832544893%"
        id="e2b0b822-5713-4b6e-a847-065f9e73b4f0"
        v-bind:style="{'color':'#000000','width':'','fontSize':'8.315999999999999px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'left','background':'#ffffff','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'','paddingTop':'','visibility':'visible','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','textDecoration':'none','zIndex':2}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>