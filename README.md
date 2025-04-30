# Python Reversing

Daftar alat, library, dan sumber daya Python untuk reverse engineering.

- [Disassembler](#disassembler)
- [Dekompiler](#dekompiler)
- [Debugger](#debugger)
- [Bytecode](#bytecode)
    - [Editor](#editor)
    - [Analisis Manual](#analisis-manual)
- [Internal Python](#internal-python)
- [Packer](#packer)
- [Ekstraktor](#ekstraktor)
- [Obfuskator](#obfuskator)
- [Deobfuskator](#deobfuskator)
- [Sumber Belajar](#sumber-belajar)

---

## Disassembler

*Alat disassembler bytecode Python.*

* [dis](https://docs.python.org/3/library/dis.html) - Modul bawaan Python untuk disassembling.
* [xdis](https://github.com/rocky/python-xdis) - Library bytecode lintas-versi dengan disassembler.
* [pycdas](https://github.com/zrax/pycdc) - Disassembler/dekompiler C++ untuk semua versi Python.

## Dekompiler

*Alat dekompilasi bytecode Python.*

* [pylingual](https://github.com/syssec-utd/pylingual) ([layanan web](https://pylingual.io/)) - Dekompiler berbasis AI untuk versi Python terbaru.
* [decompile3](https://github.com/rocky/python-decompile3) - Mendukung Python 3.7 - 3.8.
* [uncompyle6](https://github.com/rocky/python-uncompyle6) - Mendukung versi 1.0 - 3.8 (termasuk bytecode Dropbox Python 2.5).
* [pycdc](https://github.com/zrax/pycdc) - Dekompiler C++ untuk semua versi (terkadang tidak stabil).
* [snippet decompiler](https://github.com/extremecoders-re/python-snippet-decompiler) - Dekompilasi potongan bytecode individual.
* [unpyc3.7-3.10](https://github.com/greyblue9/unpyc37-3.10) - Fork dekompiler untuk Python 3.7-3.10.

## Debugger

*Debugger untuk kode sumber/bytecode Python.*

* [pdb](https://docs.python.org/3/library/pdb.html) - Debugger interaktif bawaan Python.
* [python3-trepan](https://github.com/rocky/python3-trepan) - Debugger mirip gdb dengan dukungan bytecode.
* [PyCharm debugger](https://www.jetbrains.com/pycharm/) - Debugger GUI profesional.

## Bytecode

### Editor

*Editor bytecode Python.*

* [pySpy](https://github.com/Svenskithesource/pySpy) - Editor untuk Python 3.9+.
* [xdis](https://github.com/rocky/python-xdis) - Memodifikasi bytecode secara programatik.

### Analisis Manual

*Alat bantu analisis manual bytecode.*

* [PyInjector](https://github.com/call-042PE/PyInjector) - Injector kode Python untuk proses Windows.
* [PythonForWindows](https://github.com/hakril/PythonForWindows) - Berinteraksi dengan proses Python di Windows.
* [x-python](https://github.com/rocky/x-python) - Emulator bytecode Python.
* [hypno](https://github.com/kmaork/hypno) - Injeksi kode cross-platform (bisa diinstall via `pip`).
* [PyInjecto](https://github.com/BetterWayElectronics/PyInjecto) - CLI untuk injeksi kode dan analisis proses.

## Internal Python

*Alat inspeksi internal Python.*

* [inspect](https://docs.python.org/3/library/inspect.html) - Modul bawaan untuk inspeksi objek.
* [CPython](https://github.com/python/cpython) - Kode sumber interpreter CPython.

## Packer

*Tools untuk mengemas kode Python ke executable.*

* [PyInstaller](https://pyinstaller.org/) - Packer paling populer (Windows/Linux/Mac).
* [py2exe](https://www.py2exe.org/) - Khusus Windows.
* [Cython](https://cython.org/) - Kompilasi Python ke C.
* [Nuitka](https://github.com/Nuitka/Nuitka) - Kompilasi Python ke C++.

## Ekstraktor

*Alat ekstraksi file dari executable Python.*

* [pyinstxtractor](https://github.com/extremecoders-re/pyinstxtractor) - Ekstraktor untuk PyInstaller.
* [unpy2exe](https://github.com/matiasb/unpy2exe) - Untuk py2exe (tidak terupdate).
* [nuitka-extractor](https://github.com/extremecoders-re/nuitka-extractor) - Ekstraktor untuk Nuitka.

## Obfuskator

*Tools pengaburan kode Python.*

* [Pyarmor](https://github.com/dashingsoft/pyarmor) - Obfuskator paling populer.
* [Nuitka](https://github.com/Nuitka/Nuitka) - Kompilasi ke C++ sebagai proteksi.
* [Hyperion](https://github.com/billythegoat356/Hyperion) - Transformasi kode sumber.
* [Specter/Kramer/Berserker](https://github.com/billythegoat356/) - Obfuskator berbasis `exec`.

## Deobfuskator

*Tools untuk membongkar kode terobfuskasi.*

* [PyArmor-Unpacker](https://github.com/Svenskithesource/PyArmor-Unpacker) - Untuk Pyarmor versi gratis.
* [bonedensity](https://github.com/nesrak1/bonedensity) - Bongkar Pyarmor gratis & berbayar.
* [Hyperion-deobfuscator](https://github.com/xKiian/Hyperion-deobfuscator) - Dekompilasi Hyperion.

## Sumber Belajar

*Materi pembelajaran reverse engineering Python.*

* [Blog Python Reversing](https://blog.svenskithesource.be/)
* [Panduan Nuitka](https://goatmilkk.notion.site/Nuitka-a3ac9ee7f3f240f3baa345c17f2b8aa3)
* [Analisis Code Objects](https://late.am/post/2012/03/26/exploring-python-code-objects.html)
* [Stack Frames Python](https://towardsdatascience.com/python-stack-frames-and-tail-call-optimization-4d0ea55b0542)
