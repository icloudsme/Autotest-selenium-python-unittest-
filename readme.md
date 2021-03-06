

---

 **selenium python unittest框架**


### 整体目录结构

    /selenium_python/test_case/baidu.py -----测试用例
    				/test_case/youdao.py -----测试用例
    				/test_case/webcloud.py -----私有云用例
    				/test_case/__init__.py
    				/test_case/public/login.py -----登录模块
    				/test_case/public/quit.py -----退出模块
    				/test_case/public/__init__.py
    				/data/userinfo.csv -----用户数据参数化文件
    				/report/now_time_result.html -----HTML 测试报告
    				/all_tests.py ----执行用例文件
					
### 使用：

在test_case目录下创建测试用例，执行all_tests即可


python内部自带了一个单元测试的模块，pyUnit也就是我们说的：unittest
下面是unittest模块的常用方法：

    assertEqual(a, b)     a == b      
    assertNotEqual(a, b)     a != b      
    assertTrue(x)     bool(x) is True      
    assertFalse(x)     bool(x) is False      
    assertIs(a, b)     a is b     2.7
    assertIsNot(a, b)     a is not b     2.7
    assertIsNone(x)     x is None     2.7
    assertIsNotNone(x)     x is not None     2.7
    assertIn(a, b)     a in b     2.7
    assertNotIn(a, b)     a not in b     2.7
    assertIsInstance(a, b)     isinstance(a, b)     2.7
    assertNotIsInstance(a, b)     not isinstance(a, b)     2.7
	
也有其他的unittest方法，用于执行更具体的检查，如：

   

    assertAlmostEqual(a, b)     round(a-b, 7) == 0      
    assertNotAlmostEqual(a, b)     round(a-b, 7) != 0      
    assertGreater(a, b)     a > b     2.7
    assertGreaterEqual(a, b)     a >= b     2.7
    assertLess(a, b)     a < b     2.7
    assertLessEqual(a, b)     a <= b     2.7
    assertRegexpMatches(s, re)     regex.search(s)     2.7
    assertNotRegexpMatches(s, re)     not regex.search(s)     2.7
    assertItemsEqual(a, b)     sorted(a) == sorted(b) and works with unhashable objs     2.7
    assertDictContainsSubset(a, b)     all the key/value pairs in a exist in b     2.7
    assertMultiLineEqual(a, b)     strings     2.7
    assertSequenceEqual(a, b)     sequences     2.7
    assertListEqual(a, b)     lists     2.7
    assertTupleEqual(a, b)     tuples     2.7
    assertSetEqual(a, b)     sets or frozensets     2.7
    assertDictEqual(a, b)     dicts     2.7
    assertMultiLineEqual(a, b)     strings     2.7
    assertSequenceEqual(a, b)     sequences     2.7
    assertListEqual(a, b)     lists     2.7
    assertTupleEqual(a, b)     tuples     2.7
    assertSetEqual(a, b)     sets or frozensets     2.7
    assertDictEqual(a, b)     dicts     2.7




