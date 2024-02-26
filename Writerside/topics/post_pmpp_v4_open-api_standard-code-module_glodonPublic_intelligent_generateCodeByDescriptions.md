# 根据描述信息，生成标准编码

<api-endpoint openapi-path="../api/open-api/pmpp_v4_open-api_standard-code-module_glodonPublic_intelligent_generateCodeByDescriptions.yaml" endpoint="/pmpp/v4/open-api/standard-code-module/glodonPublic/intelligent/generateCodeByDescriptions" method="post">

<request>

<sample lang="JSON">
["现浇混凝土C30","现浇混凝土C40"]
</sample>

</request>
<response type="200">

<sample>
{
    "现浇混凝土C30":{
        "code": "标准编码",
        "name": "名称",
        "unit": "单位",
        "specification": "规格型号",
        "texture": "材质"
    }, 
    "现浇混凝土C30":{
        "code": "标准编码",
        "name": "名称",
        "unit": "单位",
        "specification": "规格型号",
        "texture": "材质"
    },
}
</sample>

</response>



</api-endpoint>   