<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="1150"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="5372bc9f-ce8b-44a7-9a45-2753d6b186eb" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WImage v-bind:blank="false" v-bind:rounded="false" stretch="none"
        imageUrl="data:image/png;base64,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"
        v-bind:isEnabled="true" v-bind:thumbnail="false" blankColor="black" v-bind:aspectRatio="true"
        dataLoading="static" ncTooltipText="Please write a text to display in tooltip..."
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'update':{'type':'dataModelForDynamicType'},'propName':'imageUrl','displayName':'Value'}]}"
        ncClickBorderColor="black" ncHoverBorderColor="black" dataModelForDynamicType="string" position="absolute"
        top="0%" left="0%" v-bind:snapX="false" v-bind:snapY="false" id="59e78568-8720-4c94-a330-47a7e1cb99b6"
        v-bind:style="{'width':'1150px','height':'742px','maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderColor':'#4B74FF','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
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