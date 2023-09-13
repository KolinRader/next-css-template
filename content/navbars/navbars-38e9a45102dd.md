---
title: Navbar with black button
category: Application
paid: true
isActive: true
ltr: {"preview":"function App() {\n  const [state, setState] = React.useState(false);\n\n  // Replace javascript:void(0) paths with your paths\n  const navigation = [{\n    title: \"Features\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"Integrations\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"Customers\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"Pricing\",\n    path: \"javascript:void(0)\"\n  }];\n  React.useEffect(() => {\n    document.onclick = e => {\n      const target = e.target;\n      if (!target.closest(\".menu-btn\")) setState(false);\n    };\n  }, []);\n  return /*#__PURE__*/React.createElement(\"nav\", {\n    className: `bg-white pb-5 md:text-sm ${state ? \"shadow-lg rounded-xl border mx-2 mt-2 md:shadow-none md:border-none md:mx-2 md:mt-0\" : \"\"}`\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"gap-x-14 items-center max-w-screen-xl mx-auto px-4 md:flex md:px-8\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex items-center justify-between py-5 md:block\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\"\n  }, /*#__PURE__*/React.createElement(\"img\", {\n    src: \"https://www.floatui.com/logo.svg\",\n    width: 120,\n    height: 50,\n    alt: \"Float UI logo\"\n  })), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"md:hidden\"\n  }, /*#__PURE__*/React.createElement(\"button\", {\n    className: \"menu-btn text-gray-500 hover:text-gray-800\",\n    onClick: () => setState(!state)\n  }, state ? /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    className: \"h-6 w-6\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\",\n    clipRule: \"evenodd\"\n  })) : /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    fill: \"none\",\n    viewBox: \"0 0 24 24\",\n    strokeWidth: 1.5,\n    stroke: \"currentColor\",\n    className: \"w-6 h-6\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    strokeLinecap: \"round\",\n    strokeLinejoin: \"round\",\n    d: \"M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5\"\n  }))))), /*#__PURE__*/React.createElement(\"div\", {\n    className: `flex-1 items-center mt-8 md:mt-0 md:flex ${state ? 'block' : 'hidden'} `\n  }, /*#__PURE__*/React.createElement(\"ul\", {\n    className: \"justify-center items-center space-y-6 md:flex md:space-x-6 md:space-y-0\"\n  }, navigation.map((item, idx) => {\n    return /*#__PURE__*/React.createElement(\"li\", {\n      key: idx,\n      className: \"text-gray-700 hover:text-gray-900\"\n    }, /*#__PURE__*/React.createElement(\"a\", {\n      href: item.path,\n      className: \"block\"\n    }, item.title));\n  })), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex-1 gap-x-6 items-center justify-end mt-6 space-y-6 md:flex md:space-y-0 md:mt-0\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"block text-gray-700 hover:text-gray-900\"\n  }, \"Log in\"), /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\"\n  }, \"Sign in\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\",\n    className: \"w-5 h-5\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z\",\n    clipRule: \"evenodd\"\n  })))))));\n}","vue":{"vueCss":[],"vueTail":[]},"react":{"jsxTail":[{"code":"import { useEffect, useState } from 'react'\n\nexport default () => {\n\n    const [state, setState] = useState(false)\n\n    // Replace javascript:void(0) paths with your paths\n    const navigation = [\n        { title: \"Features\", path: \"javascript:void(0)\" },\n        { title: \"Integrations\", path: \"javascript:void(0)\" },\n        { title: \"Customers\", path: \"javascript:void(0)\" },\n        { title: \"Pricing\", path: \"javascript:void(0)\" }\n    ]\n\n    useEffect(() => {\n        document.onclick = (e) => {\n            const target = e.target;\n            if (!target.closest(\".menu-btn\")) setState(false);\n        };\n    }, [])\n\n    return (\n        <nav className={`bg-white pb-5 md:text-sm ${state ? \"shadow-lg rounded-xl border mx-2 mt-2 md:shadow-none md:border-none md:mx-2 md:mt-0\" : \"\"}`}>\n            <div className=\"gap-x-14 items-center max-w-screen-xl mx-auto px-4 md:flex md:px-8\">\n                <div className=\"flex items-center justify-between py-5 md:block\">\n                    <a href=\"javascript:void(0)\">\n                        <img\n                            src=\"https://www.floatui.com/logo.svg\"\n                            width={120}\n                            height={50}\n                            alt=\"Float UI logo\"\n                        />\n                    </a>\n                    <div className=\"md:hidden\">\n                        <button className=\"menu-btn text-gray-500 hover:text-gray-800\"\n                            onClick={() => setState(!state)}\n                        >\n                            {\n                                state ? (\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" className=\"h-6 w-6\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                                        <path fillRule=\"evenodd\" d=\"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\" clipRule=\"evenodd\" />\n                                    </svg>\n                                ) : (\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" fill=\"none\" viewBox=\"0 0 24 24\" strokeWidth={1.5} stroke=\"currentColor\" className=\"w-6 h-6\">\n                                        <path strokeLinecap=\"round\" strokeLinejoin=\"round\" d=\"M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5\" />\n                                    </svg>\n                                )\n                            }\n                        </button>\n                    </div>\n                </div>\n                <div className={`flex-1 items-center mt-8 md:mt-0 md:flex ${state ? 'block' : 'hidden'} `}>\n                    <ul className=\"justify-center items-center space-y-6 md:flex md:space-x-6 md:space-y-0\">\n                        {\n                            navigation.map((item, idx) => {\n                                return (\n                                    <li key={idx} className=\"text-gray-700 hover:text-gray-900\">\n                                        <a href={item.path} className=\"block\">\n                                            {item.title}\n                                        </a>\n                                    </li>\n                                )\n                            })\n                        }\n                    </ul>\n                    <div className=\"flex-1 gap-x-6 items-center justify-end mt-6 space-y-6 md:flex md:space-y-0 md:mt-0\">\n                        <a href=\"javascript:void(0)\" className=\"block text-gray-700 hover:text-gray-900\">\n                            Log in\n                        </a>\n                        <a href=\"javascript:void(0)\" className=\"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\">\n                            Sign in\n                            <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\" className=\"w-5 h-5\">\n                                <path fillRule=\"evenodd\" d=\"M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z\" clipRule=\"evenodd\" />\n                            </svg>\n                        </a>\n                    </div>\n                </div>\n            </div>\n        </nav>\n    )\n}","label":"App.jsx"}],"jsxCss":[]}}
rtl: {"preview":"function App() {\n  const [state, setState] = React.useState(false);\n\n  // Replace javascript:void(0) paths with your paths\n  const navigation = [{\n    title: \"المميزات\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"التكاملات\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"العملاء\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"التسعير\",\n    path: \"javascript:void(0)\"\n  }];\n  React.useEffect(() => {\n    document.onclick = e => {\n      const target = e.target;\n      if (!target.closest(\".menu-btn\")) setState(false);\n    };\n  }, []);\n  return /*#__PURE__*/React.createElement(\"nav\", {\n    className: `bg-white pb-5 md:text-sm ${state ? \"shadow-lg rounded-xl border mx-2 mt-2 md:shadow-none md:border-none md:mx-2 md:mt-0\" : \"\"}`\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"gap-x-14 items-center max-w-screen-xl mx-auto px-4 md:flex md:px-8\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex items-center justify-between py-5 md:block\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\"\n  }, /*#__PURE__*/React.createElement(\"img\", {\n    src: \"https://www.floatui.com/logo.svg\",\n    width: 120,\n    height: 50,\n    alt: \"Float UI logo\"\n  })), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"md:hidden\"\n  }, /*#__PURE__*/React.createElement(\"button\", {\n    className: \"menu-btn text-gray-500 hover:text-gray-800\",\n    onClick: () => setState(!state)\n  }, state ? /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    className: \"h-6 w-6\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\",\n    clipRule: \"evenodd\"\n  })) : /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    fill: \"none\",\n    viewBox: \"0 0 24 24\",\n    strokeWidth: 1.5,\n    stroke: \"currentColor\",\n    className: \"w-6 h-6\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    strokeLinecap: \"round\",\n    strokeLinejoin: \"round\",\n    d: \"M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5\"\n  }))))), /*#__PURE__*/React.createElement(\"div\", {\n    className: `flex-1 items-center mt-8 md:mt-0 md:flex ${state ? 'block' : 'hidden'} `\n  }, /*#__PURE__*/React.createElement(\"ul\", {\n    className: \"justify-center items-center space-y-6 md:flex md:space-x-6 md:space-x-reverse md:space-y-0\"\n  }, navigation.map((item, idx) => {\n    return /*#__PURE__*/React.createElement(\"li\", {\n      key: idx,\n      className: \"text-gray-700 hover:text-gray-900\"\n    }, /*#__PURE__*/React.createElement(\"a\", {\n      href: item.path,\n      className: \"block\"\n    }, item.title));\n  })), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex-1 gap-x-6 items-center justify-end mt-6 space-y-6 md:flex md:space-y-0 md:mt-0\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"block text-gray-700 hover:text-gray-900\"\n  }, \"\\u062A\\u0633\\u062C\\u064A\\u0644 \\u062F\\u062E\\u0648\\u0644\"), /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\"\n  }, \"\\u062A\\u0633\\u062C\\u064A\\u0644\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\",\n    className: \"w-5 h-5\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z\",\n    clipRule: \"evenodd\"\n  })))))));\n}","react":{"jsxCss":[],"jsxTail":[{"code":"import { useEffect, useState } from 'react'\n\nexport default () => {\n\n    const [state, setState] = useState(false)\n\n    // Replace javascript:void(0) paths with your paths\n    const navigation = [\n        { title: \"المميزات\", path: \"javascript:void(0)\" },\n        { title: \"التكاملات\", path: \"javascript:void(0)\" },\n        { title: \"العملاء\", path: \"javascript:void(0)\" },\n        { title: \"التسعير\", path: \"javascript:void(0)\" }\n    ]\n\n    useEffect(() => {\n        document.onclick = (e) => {\n            const target = e.target;\n            if (!target.closest(\".menu-btn\")) setState(false);\n        };\n    }, [])\n\n    return (\n        <nav className={`bg-white pb-5 md:text-sm ${state ? \"shadow-lg rounded-xl border mx-2 mt-2 md:shadow-none md:border-none md:mx-2 md:mt-0\" : \"\"}`}>\n            <div className=\"gap-x-14 items-center max-w-screen-xl mx-auto px-4 md:flex md:px-8\">\n                <div className=\"flex items-center justify-between py-5 md:block\">\n                    <a href=\"javascript:void(0)\">\n                        <img\n                            src=\"https://www.floatui.com/logo.svg\"\n                            width={120}\n                            height={50}\n                            alt=\"Float UI logo\"\n                        />\n                    </a>\n                    <div className=\"md:hidden\">\n                        <button className=\"menu-btn text-gray-500 hover:text-gray-800\"\n                            onClick={() => setState(!state)}\n                        >\n                            {\n                                state ? (\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" className=\"h-6 w-6\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                                        <path fillRule=\"evenodd\" d=\"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\" clipRule=\"evenodd\" />\n                                    </svg>\n                                ) : (\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" fill=\"none\" viewBox=\"0 0 24 24\" strokeWidth={1.5} stroke=\"currentColor\" className=\"w-6 h-6\">\n                                        <path strokeLinecap=\"round\" strokeLinejoin=\"round\" d=\"M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5\" />\n                                    </svg>\n                                )\n                            }\n                        </button>\n                    </div>\n                </div>\n                <div className={`flex-1 items-center mt-8 md:mt-0 md:flex ${state ? 'block' : 'hidden'} `}>\n                    <ul className=\"justify-center items-center space-y-6 md:flex md:space-x-6 md:space-x-reverse md:space-y-0\">\n                        {\n                            navigation.map((item, idx) => {\n                                return (\n                                    <li key={idx} className=\"text-gray-700 hover:text-gray-900\">\n                                        <a href={item.path} className=\"block\">\n                                            {item.title}\n                                        </a>\n                                    </li>\n                                )\n                            })\n                        }\n                    </ul>\n                    <div className=\"flex-1 gap-x-6 items-center justify-end mt-6 space-y-6 md:flex md:space-y-0 md:mt-0\">\n                        <a href=\"javascript:void(0)\" className=\"block text-gray-700 hover:text-gray-900\">\n                            تسجيل دخول\n                        </a>\n                        <a href=\"javascript:void(0)\" className=\"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\">\n                            تسجيل\n                            <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\" className=\"w-5 h-5\">\n                                <path fillRule=\"evenodd\" d=\"M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z\" clipRule=\"evenodd\" />\n                            </svg>\n                        </a>\n                    </div>\n                </div>\n            </div>\n        </nav>\n    )\n}","label":"App.jsx"}]},"vue":{"vueTail":[],"vueCss":[]}}
slug: /navbars
id: 92c5c5a2-3eb0-4e2a-a44c-38e9a45102dd
created_at: 1668383283523
---