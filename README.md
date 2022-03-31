#### 1. Что такое protobuf.

#### 2. Для чего нужен protobuf.
- модель данных
- контракт для внешних пользователей
- удалённый вызов процедур
- gRPC API (генерация)
- HTTP API (генерация)

#### 3. Документация.
- https://developers.google.com/protocol-buffers/docs/proto3
- https://developers.google.com/protocol-buffers/docs/style

#### 4. Объекты: сообщения (типы данных), методы.

#### 5. Имена: файлы, сообщения, функции.

#### 6. Пример описания.

#### 7. Замечания.
- значения VS указатели
- зарезервированные поля
- форматирование кода
- формат комментариев

#### 8. Копиляция (генерация) кода.
proto-demo$ protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative --proto_path=.. proto-demo/protobuf/rpc.proto