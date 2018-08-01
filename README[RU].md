<a name="оглавление"></a>


## Оглавление:
  - [@access](#access)
  - [@alias](#alias)
  - [@author](#author)
  - [@content](#content)
  - [@deprecated](#deprecated)
  - [@example](#example)
  - [@group](#group)
  - [@ignore](#ignore)
  - [@link](#link)
  - [@name](#name)
  - [@access](#access)
  - [@todo](#todo)
  - [@throw](#throw)
  - [@since](#since)
  - [@see](#see)
  - [@return](#return)
  - [@require](#require)
  - [@property](#property)
  - [@parameter](#parameter)
  - [@output](#output)
  - [@type](#type)

## API для документирования с испольщзованием [sassDoc](http://sassdoc.com)

<table>
  <thead>
    <tr>
      <th> Аннотация </th>
      <th> Описание </th>
      <th> Псевдонимы </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> <a href="#comment-range"> Диапазон комментариев </a> </td>
      <td> Диапазон комментариев </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#description"> Описание </a> </td>
      <td> Описание документированного элемента </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#access"> @access </a> </td>
      <td> Доступ к документированному элементу </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#alias"> @alias </a> </td>
      <td> Является ли документированный элемент псевдонимом другого элемента </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#author"> @author </a> </td>
      <td> Автор документального документа </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#content"> @content </a> </td>
      <td> Если документированный mixin использует директиву <code> @content </code> </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#deprecated"> @deprecated </a> </td>
      <td> Не документирован ли документированный элемент </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#example"> @example </a> </td>
      <td> Пример для документированного элемента </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#group"> @group </a> </td>
      <td> Группировать документированный элемент принадлежит </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#ignore"> @ignore </a> </td>
      <td> Игнорируемый контент </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#link"> @link </a> </td>
      <td> Ссылка, связанная с документированным товаром </td>
      <TD> @source </td>
    </tr>
    <tr>
      <td> <a href="#name"> @name </a> </td>
      <td> Название документального документа </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#output"> @output </a> </td>
      <td> Выход из документализованного mixin </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#parameter"> @parameter </a> </td>
      <td> Параметры из документализованного mixin или функции </td>
      <td> @param, @arg, @argument </td>
    </tr>
    <tr>
      <td> <a href="#property"> @property </a> </td>
      <td> Свойство документальной карты </td>
      <TD> @prop </td>
    </tr>
    <tr>
      <td> <a href="#require"> @require </a> </td>
      <td> Требования к документированному элементу </td>
      <TD> @requires </td>
    </tr>
    <tr>
      <td> <a href="#return"> @return </a> </td>
      <td> Возврат из документальной функции </td>
      <TD> @returns </td>
    </tr>
    <tr>
      <td> <a href="#see"> @see </a> </td>
      <td> Ресурс, связанный с документированным элементом </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#since"> @since </a> </td>
      <td> Список изменений для документированного элемента </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#throw"> @throw </a> </td>
      <td> Исключения, вызванные документированным элементом </td>
      <td> @throws, @exception </td>
    </tr>
    <tr>
      <td> <a href="#todo"> @todo </a> </td>
      <td> Что делать с документированным товаром </td>
      <TD> - </td>
    </tr>
    <tr>
      <td> <a href="#type"> @type </a> </td>
      <td> Описывает тип переменной </td>
      <TD> - </td>
    </tr>
  </tbody>
</table>

<a name="access"></a>

**[⬆ в начало](#оглавление)**

## @access

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Определяет доступ к документированному элементу </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> false </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <td> <code> public </code> </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, заполнители, переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Либо <code> public </code>, либо <code> private </code>. </td>
     </tr>
   </tbody>
</table>

<a name="alias"></a>

**[⬆ в начало](#оглавление)**

## @alias

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Определяет, является ли документированный элемент псевдонимом другого элемента </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> false </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, variables </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Другой элемент автоматически будет иметь ключ с именем <code> aliased </code>, содержащий имя псевдонимов. </td>
     </tr>
   </tbody>
</table>

<a name="author"></a>

**[⬆ в начало](#оглавление)**

## @author

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Описывает автора документального документа </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> True </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, заполнители, переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Разбирается как markdown.*</td>
     </tr>
   </tbody>
</table>

<a name="content"></a>

**[⬆ в начало](#оглавление)**

## @content

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Описывает использование директивы Sass <code> @content </code> в документированном mixin </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> false </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> True </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <TD> Примеси </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Разбирается как Markdown.* </td>
     </tr>
   </tbody>
</table>

<a name="deprecated"></a>

**[⬆ в начало](#оглавление)**

## @deprecated

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Определяет, является ли документированный элемент устаревшим </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> false </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, заполнители, переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Разбирается как markdown.*<br /> Сообщение не является обязательным. </td>
     </tr>
   </tbody>
</table>

<a name="example"></a>

**[⬆ в начало](#оглавление)**

## @example

<table>
  <thead>
    <tr>
      <th> Атрибут </th>
      <th> Значение </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <TD> Описание </td>
      <td> Описывает прецедент для документированного элемента с заданным языком и описанием, если указано </td>
    </tr>
    <tr>
      <TD> Несколько </td>
      <TD> True </td>
    </tr>
    <tr>
      <TD> По умолчанию </td>
      <TD> - </td>
    </tr>
    <tr>
      <TD> Псевдонимы </td>
      <TD> - </td>
    </tr>
    <tr>
      <TD> Autofilled </td>
      <TD> false </td>
    </tr>
    <tr>
      <td> Разрешено </td>
      <td> функции, mixins, заполнители, переменные </td>
    </tr>
    <tr>
      <td> Дополнительные примечания </td>
      <td> Строки, начинающиеся с <code> @ </code>, должны иметь отступ, чтобы работать правильно. <br /> Первое слово в той же строке, что и <code> @example </code>, является языком выделения синтаксиса. < br /> Поддерживаемые языки: <code> css </code>, <code> scss </code>, <code> markup </code>, <code> javascript </code>. Новые языки по требованию. <br /> Все, кроме первого слова в той же строке, что и <code> @example </code>, - это описание. <br /> Hyphen перед описанием является необязательным. <br /> Описание анализируется как markdown.*</td>
    </tr>
  </tbody>
</table>

<a name="group"></a>

**[⬆ в начало](#оглавление)**

## @group

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Определяет, к какой группе (если таковая имеется) относится к документированному элементу </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> false </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <td> <code> undefined </code> </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, заполнители, переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Группы определяют способ отображения элементов в теме по умолчанию SassDoc. <br /> Группы могут быть сглажены для дружественных имен из конфигурации (<a href="/configuration/#groups"> больше информации </a>). </td>
     </tr>
   </tbody>
</table>

<a name="ignore"></a>

**[⬆ в начало](#оглавление)**

## @ignore
<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Определяет строку, которая не будет документирована </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> True </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, заполнители, переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <TD> - </td>
     </tr>
   </tbody>
</table>

<a name="link"></a>

**[⬆ в начало](#оглавление)**

## @link

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Описывает ссылку </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> True </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <td> <code> @source </code> </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, заполнители, переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Заголовок не является обязательным. </td>
     </tr>
   </tbody>
</table>

<a name="name"></a>

**[⬆ в начало](#оглавление)**

## @name

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Укажите произвольное имя для документированного элемента </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> false </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <td> <code> item.context.name </code> </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> True </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, заполнители, переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Полезно только при необходимости переопределить самоиспользуемое имя. </td>
     </tr>
   </tbody>
</table>

<a name="output"></a>

**[⬆ в начало](#оглавление)**

## @output

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Предоставьте описание того, что печатается с помощью mixin </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> false </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <td> <code> @outputs </code> </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <TD> Примеси </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Разбирается как markdown.*</td>
     </tr>
   </tbody>
</table>

<a name="parameter"></a>

**[⬆ в начало](#оглавление)**

## @parameter

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Описывает параметр документированного элемента </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> True </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <td> <code> @arg </code>, <code> @argument </code>, <code> @param </code> </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Значение по умолчанию необязательно. <br /> Описание необязательно. Hyphen перед описанием является необязательным. <br /> Описание анализируется как markdown.*<br /> Несколько типов должны быть разделены по трубам (<code> | </code>). </td>
     </tr>
   </tbody>
</table>

<a name="property"></a>

**[⬆ в начало](#оглавление)**

## @property

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Свойства карт документов, используйте точечную нотацию, чтобы обозначить вложенность </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> True </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <td> <code> @prop </code> </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <TD> Переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Описание анализируется как markdown.*<br /> Если <code> {Тип} </code> опущен, по умолчанию он будет <code> Map </code>, чтобы сделать его более удобным для вложенных карт. < / TD>
     </tr>
   </tbody>
</table>

<a name="require"></a>

**[⬆ в начало](#оглавление)**

## @require

<table>
  <thead>
    <tr>
      <th> Атрибут </th>
      <th> Значение </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <TD> Описание </td>
      <td> Определяет, требуется ли документированному элементу любой другой элемент </td>
    </tr>
    <tr>
      <TD> Несколько </td>
      <TD> True </td>
    </tr>
    <tr>
      <TD> По умолчанию </td>
      <TD> - </td>
    </tr>
    <tr>
      <TD> Псевдонимы </td>
      <td> <code> @requires </code> </td>
    </tr>
    <tr>
      <TD> Autofilled </td>
      <TD> True </td>
    </tr>
    <tr>
      <td> Разрешено </td>
      <td> функции, mixins, заполнители, переменные </td>
    </tr>
    <tr>
      <td> Дополнительные примечания </td>
      <td> Тип необязателен; по умолчанию тип <code> function </code>. Может быть либо <code> function </code>, <code> mixin </code>, <code> variable </code>, либо <code> placeholder </code>). <br /> Если <code> {type} </code> является переменной <code> </code>, тогда знак <code> $ </code> перед именем переменной является необязательным. Наряду с знаком <code> $ </code> перед именем элемента, тип <code> {variable} </code> не является обязательным. <br /> Если <code> {type} </code> это <code> placeholder </code>, тогда знак <code>% </code> перед именем заполнителя является необязательным. Наряду с знаком <code>% </code> перед именем элемента, тип <code> {placeholder} </code> не является обязательным. <br /> Описание необязательно. Имя файла может содержать <code> :: </code>, <code>: </code> <имя_файла>: <code>: </code>, <code>: </ code >, <code>. </code> и / или <code> / </code>, когда элемент находится из внешнего ресурса. <br /> Ссылка используется как ссылка, если присутствует, иначе она пытается связать с внутренним item, иначе у него нет ссылки. <br /> Другой элемент автоматически будет иметь ключ с именем <code> usedBy </code>, содержащий имя функции, требующей его. </td>
    </tr>
  </tbody>
</table>

<a name="return"></a>

**[⬆ в начало](#оглавление)**

## @return

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Описывает оператор возврата документальной функции </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> false </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <td> <code> @returns </code> </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <TD> Функции </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Описание необязательно. Hyphen перед описанием является необязательным. <br /> Описание анализируется как markdown.*<br /> Несколько типов должны быть разделены по трубам (<code> | </code>). </td>
     </tr>
   </tbody>
</table>

<a name="see"></a>

**[⬆ в начало](#оглавление)**

## @see

<table>
  <thead>
    <tr>
      <th> Атрибут </th>
      <th> Значение </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <TD> Описание </td>
      <td> Описывает элемент, который каким-то образом связан с документированным элементом (чтобы описать зависимость, авторы должны использовать <code> @require </code>) </td>
    </tr>
    <tr>
      <TD> Несколько </td>
      <TD> True </td>
    </tr>
    <tr>
      <TD> По умолчанию </td>
      <TD> - </td>
    </tr>
    <tr>
      <TD> Псевдонимы </td>
      <TD> - </td>
    </tr>
    <tr>
      <TD> Autofilled </td>
      <TD> false </td>
    </tr>
    <tr>
      <td> Разрешено </td>
      <td> функции, mixins, заполнители, переменные </td>
    </tr>
    <tr>
      <td> Дополнительные примечания </td>
      <td> Тип необязателен; по умолчанию тип <code> function </code>. Может быть либо <code> function </code>, <code> mixin </code>, <code> variable </code>, либо <code> placeholder </code>). <br /> Если <code> {type} </code> является переменной <code> </code>, тогда знак <code> $ </code> перед именем переменной является необязательным. Наряду с знаком <code> $ </code> перед именем элемента, тип <code> {variable} </code> не является обязательным. <br /> Если <code> {type} </code> это <code> placeholder </code>, тогда знак <code>% </code> перед именем заполнителя является необязательным. Наряду с знаком <code>% </code> перед именем элемента, тип <code> {placeholder} </code> не является обязательным. </td>
    </tr>
  </tbody>
</table>

<a name="since"></a>

**[⬆ в начало](#оглавление)**

## @since

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Описывает версию, в которой реализованный или обновленный документированный элемент </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> True </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, заполнители, переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Описание необязательно. Hyphen перед описанием является необязательным. <br /> Описание анализируется как markdown.*</td>
     </tr>
   </tbody>
</table>

<a name="throw"></a>

**[⬆ в начало](#оглавление)**

## @throw

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Описывает ошибку, выписанную документированным элементом </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> True </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <td> <code> @throws </code>, <code> @exception </code> </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> True </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, placeholders </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Разбирается как markdown.*</td>
     </tr>
   </tbody>
</table>

<a name="todo"></a>

**[⬆ в начало](#оглавление)**

## @todo

<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Определяет любую задачу, связанную с документированным элементом </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> True </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <td> функции, mixins, заполнители, переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Разбирается как markdown.*</td>
     </tr>
   </tbody>
</table>

<a name="type"></a>

**[⬆ в начало](#оглавление)**

## @type
<table>
   <thead>
     <tr>
       <th> Атрибут </th>
       <th> Значение </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <TD> Описание </td>
       <td> Описывает тип документированной переменной </td>
     </tr>
     <tr>
       <TD> Несколько </td>
       <TD> false </td>
     </tr>
     <tr>
       <TD> По умолчанию </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Псевдонимы </td>
       <TD> - </td>
     </tr>
     <tr>
       <TD> Autofilled </td>
       <TD> false </td>
     </tr>
     <tr>
       <td> Разрешено </td>
       <TD> Переменные </td>
     </tr>
     <tr>
       <td> Дополнительные примечания </td>
       <td> Несколько типов должны быть разделены с помощью труб (<code> | </code>). </td>
     </tr>
   </tbody>
</table>

**[⬆ в начало](#оглавление)**