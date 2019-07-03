# 0iOS-MVC-Singleton
iOS Design Pattern MVC written in objective C with Singleton for SQLite, also does RESTful webservice back end in PHP MySQL JSON.
 
 Singleton instance share a Database SQLite.
 
 RESTful web service JSON for iOS using NSURLConnection (deprecated, yet works).
 
 Design pattern MVC with Singleton and some Unit Tests
 General Project description :
 - M Model NSURLConnection (with Protocols and Delegates) for requesting JSON data from database (database in PHP MySQL JSON)
 - M Model for SQLite (libsqlite3 framework) written in Singleton instance.
 - V View in Storyboard Scenes using a UITableView embed Navigation Controller for NavBarItem right to load from remote Database
 - C Controller implements 3 protocols (Datasource - 3 methods, Delegate only 1 method, and 1 Protocol and Delegate a 
 NSDictionary to the ViewController.
  - A Unit Test (XCTestCase) using XCTAssertTrue for testing sqlite3 database creation and database insertion data.
  
  Padrão de projeto MVC com Singleton e alguns Testes Unitários
  Descrição geral :
  - M Modelo NSURLCnnection (com Protocolo e Delegação) para requisitar dados em formato JSON de um Banco de Dados (Banco escrito em back 
  end PHP MySQL e JSON).
  - M Modelo para SQLite para iOS (libsqlite3.tbd framework) escrito em Instância única Singleton.
  - V Vista feita em Storyboard utilizando UITableView incluida Controle de Navegação para um botão superior no canto direito que 
  pressionada faz a conexão com o banco de dados via internet.
  - C Controladora implementa 3 protocolos (Datasource - 3 métodos, Delegate um único protocolo, e um protocol e Delegate que passa uma 
  NSDicitionary para a ViewController)
  - Testes Unitário (XCTestCase) usado XCAssertTrue para efetuar teste com a sqlite3 banco de dados iOS realizada com sucesso da criação
  e inserção de dados no banco de dados sqlite. 
