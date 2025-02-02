# Windows

## How does it work? 

To install **the latest version of Ritchie \(1.0.0-legacy\)** on Windows, you just have to click on the links available for each version. 

However, it is important to keep in mind **there are some requirements** before starting the installation on Windows.

### Requirements

If you wanna use efficiently Ritchie on Windows, our recommendation is to install the following programs:

* Powershell
* Cygwin

{% hint style="warning" %}
**Cygwin Configurations :**  
  
- You need to install the **make** package inside Cygwin, [as suggested here](https://stackoverflow.com/questions/17710209/how-to-run-make-from-cygwin-environment?rq=1#:~:text=Run%20the%20Cygwin%20installation%2Fconfiguration,Development%22%20or%20something%20similar%29.).  
  
- You'll also have to configure the file **/etc/nsswitch.conf** inside the folder \(/ProgramFiles\) and add this non commented line:**`db_home: /%H`**
{% endhint %}



### Instalando Versão Team 

Click on the following link to[ install Ritchie Team](https://commons-repo.ritchiecli.io/1.0.0-legacy/windows/team/rit.exe).

### Instalando Versão Single

Click on the following link to [install Ritchie Single.](https://commons-repo.ritchiecli.io/1.0.0-legacy/windows/single/rit.exe)



If you prefer, you also can follow with[ **manual installation**.](manual-installation.md)

## Use Ritchie on Windows

{% hint style="warning" %}
The PATH to use Ritchie on Windows **IS NOT** configured when you download it.  
  
As long as it hasn't been configured, the user will have to go inside the folder where the **rit.exe file** has been downloaded to execute Ritchie through this file. Example : **`rit.exe init`**
{% endhint %}

You'll find a guide about how to set a path here : [**How do I set or change the PATH system variable?**](https://www.java.com/en/download/help/path.xml)\*\*\*\*

