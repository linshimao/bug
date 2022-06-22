const e = encodeURIComponent(`lessonId=${123}`) // const e = `lessonId=${123}`
Taro.navigateTo({ url: `/pages/record-detail/record-detail?${e}` }) //
目标页打印 const { router } = getCurrentInstance() console.log(router)
