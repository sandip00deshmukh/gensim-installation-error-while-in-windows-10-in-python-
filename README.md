C:\Users\Administrator\AppData\Local\Programs\Python\Python38-32\Scripts>pip3 install gensim==3.3.0

Collecting gensim==3.3.0
  
  Using cached gensim-3.3.0.tar.gz (21.9 MB)
    
    ERROR: Command errored out with exit status 1:
     command: 'c:\users\administrator\appdata\local\programs\python\python38-32\python.exe' -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\Administrator\\AppData\\Local\\Temp\\pip-install-unfv02cf\\gensim\\setup.py'"'"'; __file__='"'"'C:\\Users\\Administrator\\AppData\\Local\\Temp\\pip-install-unfv02cf\\gensim\\setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' egg_info --egg-base 'C:\Users\Administrator\AppData\Local\Temp\pip-install-unfv02cf\gensim\pip-egg-info'
         cwd: C:\Users\Administrator\AppData\Local\Temp\pip-install-unfv02cf\gensim\
   
   Complete output (97 lines):
    Processing numpy/random\_bounded_integers.pxd.in
    Processing numpy/random\mtrand.pyx
    Traceback (most recent call last):
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\tools\cythonize.py", line 61, in process_pyx
        from Cython.Compiler.Version import version as cython_version
    ModuleNotFoundError: No module named 'Cython'

    During handling of the above exception, another exception occurred:

    Traceback (most recent call last):
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\tools\cythonize.py", line 238, in <module>
        main()
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\tools\cythonize.py", line 234, in main
        find_process_files(root_dir)
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\tools\cythonize.py", line 225, in find_process_files
        process(root_dir, fromfile, tofile, function, hash_db)
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\tools\cythonize.py", line 191, in process
        processor_function(fromfile, tofile)
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\tools\cythonize.py", line 66, in process_pyx
        raise OSError('Cython needs to be installed in Python as a module')
    OSError: Cython needs to be installed in Python as a module
    Running from numpy source directory.
    C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\setup.py:461: UserWarning: Unrecognized setuptools command, proceeding with generating Cython sources and expanding templates
      run_build = parse_setuppy_commands()
    Traceback (most recent call last):
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 154, in save_modules
        yield saved
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 195, in setup_context
        yield
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 250, in run_setup
        _execfile(setup_script, ns)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 45, in _execfile
        exec(code, globals, locals)
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\setup.py", line 488, in <module>
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\setup.py", line 469, in setup_package
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\setup.py", line 275, in generate_cython
        'TFIDF, word2vec',
    RuntimeError: Running cythonize failed!

    During handling of the above exception, another exception occurred:

    Traceback (most recent call last):
      File "<string>", line 1, in <module>
      File "C:\Users\Administrator\AppData\Local\Temp\pip-install-unfv02cf\gensim\setup.py", line 246, in <module>
        setup(
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\__init__.py", line 144, in setup
        _install_setup_requires(attrs)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\__init__.py", line 139, in _install_setup_requires
        dist.fetch_build_eggs(dist.setup_requires)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\dist.py", line 716, in fetch_build_eggs
        resolved_dists = pkg_resources.working_set.resolve(
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\pkg_resources\__init__.py", line 780, in resolve
        dist = best[req.key] = env.best_match(
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\pkg_resources\__init__.py", line 1065, in best_match
        return self.obtain(req, installer)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\pkg_resources\__init__.py", line 1077, in obtain
        return installer(requirement)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\dist.py", line 786, in fetch_build_egg
        return cmd.easy_install(req)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\command\easy_install.py", line 679, in easy_install
        return self.install_item(spec, dist.location, tmpdir, deps)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\command\easy_install.py", line 705, in install_item
        dists = self.install_eggs(spec, download, tmpdir)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\command\easy_install.py", line 890, in install_eggs
        return self.build_and_install(setup_script, setup_base)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\command\easy_install.py", line 1158, in build_and_install
        self.run_setup(setup_script, setup_base, args)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\command\easy_install.py", line 1144, in run_setup
        run_setup(setup_script, args)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 253, in run_setup
        raise
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\contextlib.py", line 131, in __exit__
        self.gen.throw(type, value, traceback)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 195, in setup_context
        yield
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\contextlib.py", line 131, in __exit__
        self.gen.throw(type, value, traceback)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 166, in save_modules
        saved_exc.resume()
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 141, in resume
        six.reraise(type, exc, self._tb)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\_vendor\six.py", line 685, in reraise
        raise value.with_traceback(tb)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 154, in save_modules
        yield saved
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 195, in setup_context
        yield
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 250, in run_setup
        _execfile(setup_script, ns)
      File "c:\users\administrator\appdata\local\programs\python\python38-32\lib\site-packages\setuptools\sandbox.py", line 45, in _execfile
        exec(code, globals, locals)
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\setup.py", line 488, in <module>
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\setup.py", line 469, in setup_package
      File "C:\Users\ADMINI~1\AppData\Local\Temp\easy_install-zjfv732u\numpy-1.18.1\setup.py", line 275, in generate_cython
        'TFIDF, word2vec',
    RuntimeError: Running cythonize failed!
    Cythonizing sources
    ----------------------------------------
ERROR: Command errored out with exit status 1: python setup.py egg_info Check the logs for full command output.

C:\Users\Administrator\AppData\Local\Programs\Python\Python38-32\Scripts>
