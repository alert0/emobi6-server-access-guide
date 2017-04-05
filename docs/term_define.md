# 术语和定义

----------
<table>
   <tr>
      <td>名称</td>
      <td>解释</td>
      <td>描述</td>
   </tr>
   <tr>
      <td>EDN</td>
      <td>Exmobi开发者中心，网址https://www.exmobi.cn</td>
      <td></td>
   </tr>
   <tr>
      <td>平台型应用</td>
      <td>指应用中集成了应用超市,通过该应用能够实现其他应用的安装，卸载及登录其他应用的相关功能</td>
      <td>平台型应用是指应用中集成了应用超市功能的相关应用，所以ExMobie应用和原生应用都有可能是平台型应用。平台型应用的本质还是ExMoblie应用或原生应用。应用超市功能的集成请参照微服务鉴权SDK集成章节。</td>
   </tr>
   <tr>
      <td>非平台应用</td>
      <td>指应用本身不具有管理其他应用的能力，作为一个独立的应用存在</td>
      <td></td>
   </tr>
   <tr>
      <td>ExMobi应用</td>
      <td>开发者在EDN中将ExMobi基座和应用插件打包生成的应用包文件</td>
      <td></td>
   </tr>
   <tr>
      <td>原生应用</td>
      <td>开发者独立开发，独立打包的应用</td>
      <td></td>
   </tr>
   <tr>
      <td>客户端</td>
      <td>泛指安装在移动设备上的应用程序，ExMobi应用也属于客户端</td>
      <td></td>
   </tr>
   <tr>
      <td>服务端</td>
      <td>安装部署在linux或Windows系统中的ExMobi平台，该平台与客户端通信，并提供管理、运营、统计、数据集成、文档转换、推送等一系列管理和数据处理服务</td>
      <td></td>
   </tr>
   <tr>
      <td>访问授权码</td>
      <td>管理平台为每个应用颁发的一个授权码，它限制了应用的访问能力</td>
      <td></td>
   </tr>
   <tr>
      <td>access_token</td>
      <td>访问接口凭证，通过微服务鉴权SDK提供的接口获取，后续的接口访问过程中均需带上改字段值才能进行合法访问。</td>
      <td></td>
   </tr>
   <tr>
      <td>sso_token</td>
      <td>非必须字段，只有服务基于通讯录服务实现sso机制时，访问这些服务时才需要携带sso_token实现免登陆。</td>
      <td>例如：A,B服务实现sso机制，在应用调用/api/auth登陆接口后获取到sso_token后，在访问A，B服务时携带sso_token可以实现免登陆流程。</td>
   </tr>
</table>