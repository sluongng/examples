platform(
  name = "sluongng_platform",
  exec_properties = {
    "OSFamily": "Linux",
    "Pool": "sluongng-test-ec2",
  },
)

genrule(
  name = "test",
  outs = ["out.txt"],
  cmd = "sleep 1000; ls -al >$@",
  tools = [":README.md"],
  tags = ["manual"],
)
