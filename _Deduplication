__author__ = 'bear_fu'
#对TXT文件进行逐行去重


def _Deduplication(NameA,NameB):
	obuff = []
	for ln in open(NameA + '.txt', encoding="utf-8"):
		if ln in obuff:
			continue
		obuff.append(ln)
	with open(NameB+'.txt', 'w', encoding="utf-8") as handle:
		handle.writelines(obuff)
		print("ok")

if __name__ == '__main__':
	_Deduplication("A", "B")
	print("去重终了")

