# PostgreSQL

# Intro, 簡介

作為 RDB 的代表之一， PostgreSQL 查詢引擎（作為資料庫管理的大腦）具有強大的能力。其中，查詢敘述是否以最優的方式來執行與查詢引擎關係密切，除了查詢引擎以外，查詢計畫和執行計畫也影響資料庫在查詢時的效能表現，而 PostgreSQL 具有一套最佳化查詢的策略，並且開放了最佳化策略實現介面予核心開發者，讓使用者能靈活使用適用於特定應用場景的的自有最佳化策略。

查詢引擎做為連接伺服器和儲存引擎層的中間層：



                        Storage Engine (快取管理)
                        
                        
                         Query Engine (語法樹到查詢樹->邏輯最佳化->查詢存取路徑)
                         
                         
                        Server Framework
                        

  
  
                        
                        
  
                        
                        
