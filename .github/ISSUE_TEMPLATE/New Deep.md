name: Create New DEEP
description: https://deep.donedone.me
title: "input your title"
labels: [DEEP]
body:
- type: textarea
  attributes:
    label: 요약
    description: (셍략 가능)
  validations:
    required: false
- type: textarea
  attributes:
    label: 필요한 이유
    description: (`product` 유형은 생략 가능)
  validations:
    required: false
- type: textarea
  attributes:
    label: 목표
    description: (필수)
  validations:
    required: true
- type: textarea
  attributes:
    label: 추후 목표
    description: (생략 가능)
  validations:
    required: false
- type: textarea
  attributes:
    label: 계획
    description: (필수)
  validations:
    required: true
- type: textarea
  attributes:
    label: 논의 사항
    description: (생략 가능)
  validations:
    required: false
