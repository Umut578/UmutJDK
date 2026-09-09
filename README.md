# UmutJDK 10 (2wb2a1-snapshot)

[**TR**](#türkçe) | [**EN**](#english)

---

<a name="türkçe"></a>
## 🇹🇷 Türkçe

UmutJDK, **ARM64 (aarch64) Linux** ve Android/Termux ortamları için özel olarak derlenmiş, özelleştirilmiş bir OpenJDK 17 dağıtımıdır.

### 📌 Özellikler

* **Geliştirici / Vendor:** Umut Software
* **Kod Adı:** `2wb2a1-snapshot`
* **Hedef Mimarisi:** `linux-aarch64`
* **Temel JDK Sürümü:** `17.0.21-internal`
* **Derleyici Toolchain:** Clang / LLVM (Termux Native Build)
* **Web Sitesi:** [um22jdk3366.vercel.app](https://um22jdk3366.vercel.app)

### 🚀 Kurulum ve Kullanım

```bash
# 1. Ham binary arşivini indirin:
wget [https://github.com/Umut578/UmutJDK/raw/main/UmutJDK-17-2wb2a1-arm64.tar.gz](https://github.com/Umut578/UmutJDK/raw/main/UmutJDK-17-2wb2a1-arm64.tar.gz)

# 2. Arşivi istediğiniz bir dizine çıkarın:
mkdir -p ~/UmutJDK
tar -xzf UmutJDK-17-2wb2a1-arm64.tar.gz -C ~/UmutJDK

# 3. JAVA_HOME çevre değişkenini tanımlayın ve PATH yoluna ekleyin:
export JAVA_HOME=$HOME/UmutJDK
export PATH=$JAVA_HOME/bin:$PATH

# 4. Kurulumu doğrulayın:
java -version
🎮 Uyumlu Başlatıcılar (Launchers)
UmutJDK, ARM64 mimarisinde çalışan tüm özel Minecraft başlatıcıları ve Java uygulamaları ile tam uyumludur:
PojavLauncher
SKLauncher
TL Legacy
Mojo Launcher
<a name="english"></a>
🇬🇧 English
UmutJDK is a custom OpenJDK 17 distribution built specifically for ARM64 (aarch64) Linux and Android/Termux environments.
📌 Features
Vendor: Umut Software
Codename: 2wb2a1-snapshot
Target Architecture: linux-aarch64
JDK Base Version: 17.0.21-internal
Compiler Toolchain: Clang / LLVM (Termux Native Build)
Website: um22jdk3366.vercel.app
🚀 Installation & Usage
# 1. Download the raw binary archive:
wget [https://github.com/Umut578/UmutJDK/raw/main/UmutJDK-17-2wb2a1-arm64.tar.gz](https://github.com/Umut578/UmutJDK/raw/main/UmutJDK-17-2wb2a1-arm64.tar.gz)

# 2. Extract the archive into your preferred directory:
mkdir -p ~/UmutJDK
tar -xzf UmutJDK-17-2wb2a1-arm64.tar.gz -C ~/UmutJDK

# 3. Export JAVA_HOME and update your PATH:
export JAVA_HOME=$HOME/UmutJDK
export PATH=$JAVA_HOME/bin:$PATH

# 4. Verify the installation:
java -version
🎮 Launcher Compatibility
​UmutJDK is fully optimized for custom game launchers and Java runtimes operating on ARM64:
​PojavLauncher
​SKLauncher
​TL Legacy
​Mojo Launcher
​📄 License / Lisans
​UmutJDK is distributed under the GNU General Public License v3 with the Classpath Exception (GPLv3 + CE), same as OpenJDK.
