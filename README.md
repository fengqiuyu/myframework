  resteasy+spring+mybatis搭建分布式环境。
  摒弃掉servlet这种臃肿的东西，所以不再使用j2ee服务器，采用token+restful+netty作为接口通信和安全验证，方便各种平台调用。
  其中parent为父工程，core为核心工程，其中有一个叫做main的类启动服务器。
  system工程为后端服务，system-web为前端工程。
  
