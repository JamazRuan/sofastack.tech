---
draft: false
title: "SOFATracer"
description: "SOFATracer 是蚂蚁金服开发的基于 OpenTracing 规范 的分布式链路跟踪系统。"
github: "https://github.com/sofastack/sofa-tracer"
level: "main"
weight: 3
icon: "/img/icons/sofatracer.png"
sidebar:
  - title: 'SOFATracer 介绍'
    link: 'overview'
  - title: '基础术语'
    link: 'explanation'
  - title: 'TraceId 和 SpanId 生成规则'
    link: 'traceid-generated-rule'
  - title: '快速开始'
    sub:
      - tilte: '快速开始指南'
        link: 'component-access'
      - title: 'Spring MVC 埋点接入'
        link: 'usage-of-mvc'
      - title: 'HttpClient 埋点接入'
        link: 'usage-of-httpclient'
      - title: 'DataSource 埋点接入'
        link: 'usage-of-datasource'
      - title: 'RestTemplate 埋点接入'
        link: 'usage-of-resttemplate'
      - title: 'OkHttp 埋点接入'
        link: 'usage-of-okhttp'
      - title: 'Dubbo 埋点接入'
        link: 'usage-of-dubbo'
      - title: 'OpenFeign 埋点接入'
        link: 'usage-of-openfeign'
  - title: '功能特性'
    sub:
      - title: '应用日志打印 traceId 和 spanId'
        link: 'print-traceid-spanid'
      - title: '异步线程处理'
        link: 'async'
      - title: '采样模式'
        link: 'sampler'
      - title: '上报数据至 Zipkin'
        link: 'report-to-zipkin'
  - title: 'SOFATracer 工具类'
    link: 'utils'
  - title: 'SOFATracer 配置项'
    link: 'configuration'
  - title: '日志格式'
    sub:
      - title: 'Spring MVC 日志'
        link: 'log-format-springmvc'
      - title: 'HttpClient 日志'
        link: 'log-format-httpclient'
      - title: 'DataSource 日志'
        link: 'log-format-datasource'
      - title: 'SOFARPC 日志'
        link: 'log-format-sofarpc'
      - title: 'OkHttp 日志'
        link: 'log-format-okhttp'
      - title: 'RestTemplate 日志'
        link: 'log-format-resttemplate'
      - title: 'Dubbo 日志'
        link: 'log-format-dubbo'
      - title: 'OpenFeign 日志'
        link: 'log-format-openfeign'
  - title: '发展路线'
    link: 'roadmap'
---
