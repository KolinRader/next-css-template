---
title: Basic Stats
category: Marketing
paid: false
isActive: true
ltr: {"vue":{"vueTail":[],"vueCss":[]},"react":{"jsxTail":[{"code":"export default () => {\n\n    const stats = [\n        {\n            data: \"35K\",\n            title: \"Customers\"\n        },\n        {\n            data: \"10K+\",\n            title: \"Downloads\"\n        },\n        {\n            data: \"40+\",\n            title: \"Countries\"\n        },\n        {\n            data: \"30M+\",\n            title: \"Total revenue\"\n        },\n    ]\n\n    return (\n        <section className=\"py-14\">\n            <div className=\"max-w-screen-xl mx-auto px-4 md:px-8\">\n                <ul className=\"flex flex-col items-center justify-center gap-x-12 gap-y-10 sm:flex-row sm:flex-wrap md:gap-x-24\">\n                    {\n                        stats.map((item, idx) => (\n                            <li key={idx} className=\"text-center\">\n                                <h4 className=\"text-4xl text-gray-800 font-semibold\">{item.data}</h4>\n                                <p className=\"mt-3 text-gray-600 font-medium\">{item.title}</p>\n                            </li>\n                        ))\n                    }\n                </ul>\n            </div>\n        </section>\n    )\n}","label":"App.jsx"}],"jsxCss":[]},"preview":"function App() {\n  const stats = [{\n    data: \"35K\",\n    title: \"Customers\"\n  }, {\n    data: \"10K+\",\n    title: \"Downloads\"\n  }, {\n    data: \"40+\",\n    title: \"Countries\"\n  }, {\n    data: \"30M+\",\n    title: \"Total revenue\"\n  }];\n  return /*#__PURE__*/React.createElement(\"section\", {\n    className: \"py-14\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"max-w-screen-xl mx-auto px-4 md:px-8\"\n  }, /*#__PURE__*/React.createElement(\"ul\", {\n    className: \"flex flex-col items-center justify-center gap-x-12 gap-y-10 sm:flex-row sm:flex-wrap md:gap-x-24\"\n  }, stats.map((item, idx) => /*#__PURE__*/React.createElement(\"li\", {\n    key: idx,\n    className: \"text-center\"\n  }, /*#__PURE__*/React.createElement(\"h4\", {\n    className: \"text-4xl text-gray-800 font-semibold\"\n  }, item.data), /*#__PURE__*/React.createElement(\"p\", {\n    className: \"mt-3 text-gray-600 font-medium\"\n  }, item.title))))));\n}"}
rtl: {"preview":"function App() {\n  const stats = [{\n    data: \"35K\",\n    title: \"عملاء\"\n  }, {\n    data: \"10K+\",\n    title: \"تنزيلات\"\n  }, {\n    data: \"40+\",\n    title: \"بلدان\"\n  }, {\n    data: \"30M+\",\n    title: \"إجمالي الإيرادات\"\n  }];\n  return /*#__PURE__*/React.createElement(\"section\", {\n    className: \"py-14\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"max-w-screen-xl mx-auto px-4 md:px-8\"\n  }, /*#__PURE__*/React.createElement(\"ul\", {\n    className: \"flex flex-col items-center justify-center gap-x-12 gap-y-10 sm:flex-row sm:flex-wrap md:gap-x-24\"\n  }, stats.map((item, idx) => /*#__PURE__*/React.createElement(\"li\", {\n    key: idx,\n    className: \"text-center\"\n  }, /*#__PURE__*/React.createElement(\"h4\", {\n    className: \"text-4xl text-gray-800 font-semibold\"\n  }, item.data), /*#__PURE__*/React.createElement(\"p\", {\n    className: \"mt-3 text-gray-600 font-medium\"\n  }, item.title))))));\n}","react":{"jsxCss":[],"jsxTail":[{"code":"export default () => {\n\n    const stats = [\n        {\n            data: \"35K\",\n            title: \"عملاء\"\n        },\n        {\n            data: \"10K+\",\n            title: \"تنزيلات\"\n        },\n        {\n            data: \"40+\",\n            title: \"بلدان\"\n        },\n        {\n            data: \"30M+\",\n            title: \"إجمالي الإيرادات\"\n        },\n    ]\n\n    return (\n        <section className=\"py-14\">\n            <div className=\"max-w-screen-xl mx-auto px-4 md:px-8\">\n                <ul className=\"flex flex-col items-center justify-center gap-x-12 gap-y-10 sm:flex-row sm:flex-wrap md:gap-x-24\">\n                    {\n                        stats.map((item, idx) => (\n                            <li key={idx} className=\"text-center\">\n                                <h4 className=\"text-4xl text-gray-800 font-semibold\">{item.data}</h4>\n                                <p className=\"mt-3 text-gray-600 font-medium\">{item.title}</p>\n                            </li>\n                        ))\n                    }\n                </ul>\n            </div>\n        </section>\n    )\n}","label":"App.jsx"}]},"vue":{"vueTail":[],"vueCss":[]}}
slug: /stats
id: c7c2c81b-7dfb-460d-8b66-aa9fbac873a9
created_at: 1671314660130
---