# SIMPLE JMETER FRAMEWORK

This is a simple JMeter framework mainly constructed with:
  1) Keyword driven testing
  2) Passing test parameters from multiple property files. (property file reader)
  3) Test Fragement - this is special holder of test request and executed them only when it is called from Threadgroup.
  4) Module controller - this controller holds the commonly used test request and can be called as function to executed. example: login scenario
