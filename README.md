# MCT 的 GitHub 使用者指南

Microsoft Azure 等雲端服務會經常更新，這會導致 Microsoft 認證訓練人員（MCT）在教授課程和實驗室步驟時面臨挑戰，不再符合我們的雲端服務。 . 由於變更的頻率和發生變更時可能沒有任何通知的事實，課程開發小組很難快速識別和調整實驗室變更。

為了解決這些問題，我們使用 GitHub 來發佈涵蓋 Azure 等雲端服務課程的實驗室步驟和實驗室腳本。 使用 GitHub 可讓課程的作者和 MCT 在雲端服務變更時保持實驗室內容最新狀態。 使用 GitHub 可讓 MCT 提供實驗室變更的意見反應和建議，然後課程作者可以立即更新實驗室步驟和腳本。

當您準備教授這些課程時，您應該從 GitHub 下載適當的檔案，以確保您使用最新的實驗室步驟和腳本。

本指南適用於 GitHub 新手的 MCT。 它提供連線到 GitHub、下載和列印課程教材、更新學生在實驗室中使用的腳本，以及說明如何協助確保課程的內容維持最新狀態的步驟。

> **注意**：Microsoft Learning 支援在 GitHub 上存取檔案，並支持流覽 GitHub 網站，僅限於教學本課程的 MCT。

GitHub 不應該用來討論課程中的技術內容，或如何準備課程或其實驗室。 它特別要解決實驗室中的變更。

 
> **注意**：若要討論課程和示範的一般意見，或如何準備課程，請使用MCT論壇。

## 區段

- [GitHub 術語](https://microsoftlearning.github.io/MCT-User-Guide/terminology/)

- [接收更新通知並共同作業專案](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/)

- 建議變更或提交問題給實驗室指示

## GitHub 術語

GitHub 引進了可能不熟悉的術語。 下列清單包含本檔中使用的詞彙和概念。 不過，如需 GitHub 詞彙的完整清單，請參閱 [GitHub 詞彙](https://docs.github.com/en/get-started/quickstart/github-glossary)。

| 詞彙| 說明 |
| - | - |
| Git 和 GitHub| Git 是開放原始碼的變更追蹤程式，而 GitHub 是建置在 Git 上的網站/解決方案。 還有其他網站和解決方案會使用 Git 作為其後端。 您將主要使用 GitHub 進行開放原始碼（公用）開發專案，而且這些專案是免費的。 不過，如果您想要將 GitHub 用於私人而非 開放原始碼 的專案，則必須註冊付費版本。 |
| 存放庫或存放庫| GitHub 中的每個項目都位於存放庫或存放庫。 存放庫包含專案的所有檔案，包括檔，並支援修訂歷程記錄。 存放庫可以是公用或私人。 您可以在電腦硬碟上擁有存放庫的本機複本，或使用 GitHub 內的存放庫。 |
| Markdown| 這是可用於建立文件的文字文件格式。 它是以文字為基礎且非常簡單的更新，可讓您在共同作業期間輕鬆使用。 GitHub 接著會將它轉譯為 HTML。 |
| GitHub 類別 Markdown （GFM）| Markdown 檔格式有許多變化或口味。 GitHub 版本通常稱為 GFM，是 Markdown 最常見的變化之一。 如需 GFM 的詳細資訊，以及如何針對 GFM 檔使用標記格式，請參閱 在 https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/GitHub 上開始使用撰寫和格式化。 |
| 分支| 這是另一個存放庫的復本，其位於 GitHub 帳戶中，與位於原始存放庫的分支相比。 請參閱下方的「分支」。 |
| 分支| 這是與原始存放庫位於相同存放庫中的存放庫複本。 您可以合併分支與原始分支。 |
| 擷取| 這是從在線存放庫擷取最新變更複本的程式。 不過，擷取不會合併變更。 |
| 提取]| 這是從在線存放庫擷取最新變更，並將其與本機變更合併的程式。 |
| 合併| 這是從某個分支擷取變更並套用至另一個分支的程式。 這包括從在線存放庫擷取變更，然後將變更套用至該存放庫的本機版本。 |
| 提取要求| 這是使用者提交之存放庫的一組建議變更，而存放庫的擁有者或共同作業者接著可以接受或拒絕提取要求。 |
| 推送| 這是傳送或提交本機變更至在線存放庫的程式。 |
| 共同作業者| 這是有權新增、刪除或變更存放庫內容的 GitHub 使用者。 |

## 接收更新通知、建議變更，以及在專案上共同作業

您可以設定 GitHub 體驗，以便在 GitHub 存放庫發生更新時收到通知。 有幾種方式可以註冊通知，其中許多方式都與您可以在專案上共同作業的許多方式有關。 若要接收通知，您可以執行下列動作。

| 動作| 描述 |
| - | - |
| [監看存放庫](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/watching/)| 當您監看存放庫時，GitHub 會自動為您訂閱針對該特定存放庫建立的任何新提取要求或問題通知。 您會自動監看您所建立的任何存放庫，或您是共同作業者。 |
| [提取要求](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| 當您建立提取要求並建議存放庫擁有者接受您所做的變更時，您會自動訂閱以接收有關提取要求相關討論的通知。 若要建立提取要求，您必須先建立分支。 |
| [註解](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| 當您對其他人的提取要求提出意見時，GitHub 會自動訂閱與該批注相關的論壇，或者您可以手動訂閱論壇。 |
| [問題](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| 問題是與存放庫相關的建議、問題或要求。 每個問題都有自己的討論區，而且您可以訂閱問題，或 GitHub 會自動訂閱您所建立的問題。 |
| [提到](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/mention/)| 當另一位使用者在交談中提及您時，使用 GitHub 用戶名稱 （[@username](https://github.com/username)）， GitHub 會自動訂閱您討論。 |

> **注意**：您可以修改收到通知的方式和時機，也可以取消訂閱任何或所有討論。

## 提交問題或建議實驗室指示的變更

如果您有建議或在實驗室中遇到錯誤，您可以提交提取要求並記錄問題。 如果您已經知道錯誤的修正程序，建議您提交提取要求;否則，請提交問題。

| 動作| 描述 |
| - | - |
| [提取要求](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| 當您建立提取要求並建議存放庫的擁有者接受您所做的變更時，您會自動訂閱接收有關提取要求相關討論的通知。 若要建立提取要求，您必須先建立分支。 |
| [註解](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| 當您對其他人的提取要求提出意見時，GitHub 會自動將您訂閱至該批注的相關論壇，或者您可以手動訂閱論壇。 |
| [問題](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| 問題是與存放庫相關的建議、問題或要求。 每個問題都有自己的討論。 您可以訂閱問題，或 GitHub 會自動訂閱您所建立的問題。 |
