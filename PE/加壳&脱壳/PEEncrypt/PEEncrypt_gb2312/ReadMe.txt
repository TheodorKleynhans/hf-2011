{******************************************************************************}
{ Author:    Liwuyue                                                           }
{ Email:     smokingroom@sina.com                                              }
{ Home page: http://www.programmerlife.com                                     }
{ built:     2005-03-08                                                        }
{******************************************************************************}

这个小软件通过在可执行文件(.exe)的尾部添加一个新节（Section),并且修改PE的入口地址，使可执行文件在运行时，跳出一个输入密码的对话框，从而实现了简单的加密。

源程序采用Delphi 6.0编写， 兼有少量的asm代码，用於可执行文件的加密。作者在[大富翁论坛]的ID为smokingroom, 希望能和大家交流^_^
如需传播，请保留作品的完整性！

参考作品：罗聪先生的[LC Crypto :: v0.1]，主页http://www.LuoCong.com，在此表示感谢！
