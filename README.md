# defects4jjar
Notes:

Math 9 : BUILD FAILED
/tmp/Math_9_f/build.xml:220: There were test failures.
Modified build.xml. Delete line 220. 
       <fail message="There were test failures.">
           <condition>
               <and>
                   <istrue value="${test.failonerror}"/>
                   <isset property="test.failed"/>
               </and>
           </condition>
       </fail>
Then test results are ignored and jar file generated.

Math 92 - 106:
Build Failed. Cannot pass testcases.
