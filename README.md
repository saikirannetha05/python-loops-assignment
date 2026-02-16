# python-loops-assignment
# temperature_analysis.py
temps_celsius = np.array([22,25,28,24,26])
temps_fahrenheit = temps_celsius*1.8+32
print("celsius:",temps_celsius)
print("fahrenheit:",temps_fahrenheit)
average_fahrenheit=np.round(np.mean(temps_fahrenheit),1)
print("average fahrenheit:",average_fahrenheit)
#
scores = np.array([85,90,78,92,88,76,95,82,89,91,87,84])
print("shape:",scores.shape)
print("total elements:",scores.size)
print("highest score:",np.max(scores))
print("lowest score:",np.min(scores)
print("range:",np.max(scores)-np.min(scores))
#
import time
np_array=np.arange(1,500001)
py_list=list(range(1,500001))
start+time.tme()
py.sum=sum(py_list)
py_time=time.time-start
print("NumPy sum:",np_sum)
print("python sum:',py_sum)
print("NUmPy time:{:.4f}seconds".format(np_time))
print("python time:{:.4f}seconds".format(py_time))
faster=py_time/np_time
print("NumPy is{:.1f}xfaster".format(faster))
