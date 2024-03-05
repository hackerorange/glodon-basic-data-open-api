# 判断当前用户是有可以修改某组织下的材料字典数据

<api-endpoint openapi-path="../api/open-api/pmpp_v4_open-api_material-module_organizations_{orgId}_userAuthorizations.yaml" endpoint="/pmpp/v4/open-api/material-module/organizations/{orgId}/userAuthorizations" method="get">

<response type="200">

<sample>
{
    "organizationLevel": {
        "isAvailable": true,
        "reason": ""
    },
    "tenantLevel": {
        "isAvailable": false,
        "reason": "该租户已经做过集成"
    }
}
</sample>

</response>

</api-endpoint>   