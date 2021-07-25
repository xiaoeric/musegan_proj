import pypianoroll as ppr

mt = ppr.read("fourtracks/000206b_.mid")
mt.save("test.npz")