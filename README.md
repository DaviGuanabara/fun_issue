# fun_issue
there is a issue that I can't fix.

at *Unit text*, the follow error message is thrown:

...FF
======================================================================
FAIL: test_run (__main__.TestMethods)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "<ipython-input-13-90d75d2cf513>", line 55, in test_run
    self.assertTrue(np.allclose(network.run(inputs), 0.09998924))
AssertionError: False is not true

======================================================================
FAIL: test_train (__main__.TestMethods)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "<ipython-input-13-90d75d2cf513>", line 43, in test_train
    [-0.03172939]])))
AssertionError: False is not true

----------------------------------------------------------------------
Ran 5 tests in 0.006s

FAILED (failures=2)
Out[13]:
<unittest.runner.TextTestResult run=5 errors=0 failures=2>
