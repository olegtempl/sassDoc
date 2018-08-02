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

## API для документирования scss\sass с использованием [sassDoc](http://sassdoc.com)

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
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#description"> Описание </a> </td>
      <td> Описание документируемого элемента </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#access"> @access </a> </td>
      <td> Доступ к документированному элементу </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#alias"> @alias </a> </td>
      <td> Является ли документированный элемент псевдонимом другого элемента </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#author"> @author </a> </td>
      <td> Автор документируемого элемента </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#content"> @content </a> </td>
      <td> Если документированный mixin использует директиву <code> @content </code> </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#deprecated"> @deprecated </a> </td>
      <td> Маркирует документируемый элемент устаревшим и не рекомендуемым </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#example"> @example </a> </td>
      <td> Пример использования документируемого элемента </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#group"> @group </a> </td>
      <td> Документированный элемент принадлежит следующей группе </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#ignore"> @ignore </a> </td>
      <td> Игнорируемый контент </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#link"> @link </a> </td>
      <td> Ссылка, связанная с документируемым элементом </td>
      <td> @source </td>
    </tr>
    <tr>
      <td> <a href="#name"> @name </a> </td>
      <td> Название документируемого элемента </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#output"> @output </a> </td>
      <td> Описывает возвращаемое значение документируемым mixin </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#parameter"> @parameter </a> </td>
      <td> Описывает параметры передаваемые в документируемый mixin или function </td>
      <td> @param, @arg, @argument </td>
    </tr>
    <tr>
      <td> <a href="#property"> @property </a> </td>
      <td> Свойство документируемой карты </td>
      <td> @prop </td>
    </tr>
    <tr>
      <td> <a href="#require"> @require </a> </td>
      <td> Описывает требуется ли документированному элементу любой другой элемент  </td>
      <td> @requires </td>
    </tr>
    <tr>
      <td> <a href="#return"> @return </a> </td>
      <td> Описывает возвращаемое значение документируемой функции </td>
      <td> @returns </td>
    </tr>
    <tr>
      <td> <a href="#see"> @see </a> </td>
      <td> Описывает элемент связанный с документируемым элементом </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#since"> @since </a> </td>
      <td> Описывает версию, в которой реализован или обновлен документируемый элемент </td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#throw"> @throw </a> </td>
      <td> Описывает ошибку, исключение вызываемую документированным элементом </td>
      <td> @throws, @exception </td>
    </tr>
    <tr>
      <td> <a href="#todo"> @todo </a> </td>
      <td> Описывает любые задачи на будущее, связанные с документируемым элементом</td>
      <td> - </td>
    </tr>
    <tr>
      <td> <a href="#type"> @type </a> </td>
      <td> Описывает тип документируемой переменной </td>
      <td> - </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Определяет доступ к документируемому элементу  </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе ???</td>
       <td> false </td>
     </tr>
     <tr>
       <td> Значение Значение по умолчанию </td>
       <td> <code> public </code> </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, placeholders, variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td>
       <td> Определяет, является ли документируемый элемент псевдонимом другого элемента </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе в</td>
       <td> false </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Другой элемент автоматически будет иметь ключ с именем <code> aliased </code>, содержащий имя псевдонима. </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Описывает автора документируемого элемента </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> true </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, placeholders, variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Анализируется как <code> markdown.* </code> </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Описывает использование директивы Sass <code> @content </code> в документируемом mixin </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> false </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> true </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> Примеси </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Анализируется как <code> markdown.* </code> </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Определяет, является ли документированный элемент устаревшим и не рекомендуемым </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> false </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, placeholders, variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Анализируется как <code> markdown.* </code> <br /> Сообщение не является обязательным. </td>
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
       <th> Описание </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Описание </td> 
      <td> Описывает примеры для документируемого элемента с заданным языком и значением, если они точно определены </td>
    </tr>
    <tr>
      <td> Многократное использование в одном документируемом элементе</td>
      <td> true </td>
    </tr>
    <tr>
      <td> Значение по умолчанию </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Псевдонимы </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Автозаполнение </td>
      <td> false </td>
    </tr>
    <tr>
      <td> Допускаеться использовать в </td>
      <td> functions, mixins, placeholders, variables </td>
    </tr>
    <tr>
      <td> Дополнительные сведения </td>
      <td> Строки, начинающиеся с <code> @ </code>, должны иметь отступ, иначе не будет работать. <br /> Первое слово в той же строке, что и <code> @example </code>, является языком задокументированного синтаксиса. <br /> Поддерживаемые языки: <code> css </code>, <code> scss </code>, <code> markup </code>, <code> javascript </code>. Новые языки по требованию. <br /> Все, кроме первого слова в той же строке, что и <code> @example </code>, - это значение. <br /> Дефис перед значением необязателен, <br /> значение анализируется как <code> markdown.* </code></td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Определяет, к какой группе (если таковая имеется) относится к документируемый элемент </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> false </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> <code> undefined </code> </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, placeholders, variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Группы определяют способ отображения элементов в SassDoc теме Значение по умолчанию . <br /> Группы могут быть похожими на имена (<a href="http://sassdoc.com/configuration/#groups"> из конфигурации </a>). </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Определяет строку, которая являеться документированой </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> true </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, placeholders, variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> - </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Описывает ссылку связанную с документируемым элементом</td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> true </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> <code> @source </code> </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, placeholders, variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Подпись не является обязательной. </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Укажите произвольное имя для документируемого элемента </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> false </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> <code> item.context.name </code> </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> true </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, placeholders, variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Стоит использовать при необходимости переопределить самоиспользуемое имя. </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Предоставьте значение того, что получаеться на выходе после использования mixin </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> false </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> <code> @outputs </code> </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> Примеси </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Анализируется как <code> markdown.* </code></td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Описывает параметры передаваемые в документируемый mixin или function   </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> true </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> <code> @arg </code>, <code> @argument </code>, <code> @param </code> </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Значение Значение по умолчанию необязательно. <br /> Описание необязательно. Дефис перед значением является необязательным. <br /> Описание анализируется как  <code> markdown.*</code><br /> При указании нескольких параметров, они должны быть разделены разделителем (<code> | </code>). </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Карта свойств элементов, используйте точечную нотацию, чтобы обозначить вложенность. </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> true </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> <code> @prop </code> </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Описание анализируется как <code> markdown.*</code><br /> Если <code> {Тип} </code> будет опущен,то Значение по умолчанию он будет <code> Map </code>, чтобы сделать его более удобным для вложенных карт. </td>
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
       <th> Описание </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Описание </td> 
      <td> Определяет, требуется ли документированному элементу любой другой элемент </td>
    </tr>
    <tr>
      <td> Многократное использование в одном документируемом элементе</td>
      <td> true </td>
    </tr>
    <tr>
      <td> Значение по умолчанию </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Псевдонимы </td>
      <td> <code> @requires </code> </td>
    </tr>
    <tr>
      <td> Автозаполнение </td>
      <td> true </td>
    </tr>
    <tr>
      <td> Допускаеться использовать в </td>
      <td> functions, mixins, placeholders, variables </td>
    </tr>
    <tr>
      <td> Дополнительные сведения </td>
      <td> Тип необязателен; Значение по умолчанию тип <code> function </code>. Может быть либо <code> function </code>, <code> mixin </code>, <code> variable </code>, либо <code> placeholder </code>). <br /> Если <code> {type} </code> является переменной <code> </code>, тогда знак <code> $ </code> перед именем переменной является необязательным. Наряду с знаком <code> $ </code> перед именем элемента, тип <code> {variable} </code> не является обязательным. <br /> Если <code> {type} </code> это <code> placeholder </code>, тогда знак <code>% </code> перед именем заполнителя является необязательным. Наряду с знаком <code>% </code> перед именем элемента, тип <code> {placeholder} </code> не является обязательным. <br /> значение необязательно. Имя файла может содержать <code> :: </code>, <code>: </code> <имя_файла>: <code>: </code>, <code>: </ code >, <code>. </code> и / или <code> / </code>, когда элемент от внешнего источника. <br /> Ссылка используется как ссылка, если присутствует, иначе она пытается связаться с внутренним элементом, иначе у него нет ссылки. <br /> Другой элемент автоматически будет иметь ключ с именем <code> usedBy </code>, содержащий имя functions или требующей его. </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Описывает возвращаемое значение документируемой function </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> false </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> <code> @returns </code> </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Описание необязательно. Дефис перед значением является необязательным. <br /> значение анализируется как <code>markdown.*</code><br /> При указании нескольких значений, они должны быть разделены разделителем (<code> | </code>). </td>
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
       <th> Описание </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Описание </td> 
      <td> Описывает элемент, который каким-то образом связан с документированным элементом (чтобы описать зависимость, авторы должны использовать <code> @require </code>) </td>
    </tr>
    <tr>
      <td> Многократное использование в одном документируемом элементе</td>
      <td> true </td>
    </tr>
    <tr>
      <td> Значение по умолчанию </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Псевдонимы </td>
      <td> - </td>
    </tr>
    <tr>
      <td> Автозаполнение </td>
      <td> false </td>
    </tr>
    <tr>
      <td> Допускаеться использовать в </td>
      <td> functions, mixins, placeholders, variables </td>
    </tr>
    <tr>
      <td> Дополнительные сведения </td>
      <td> Тип необязателен; Значение по умолчанию тип <code> function </code>. Может быть либо <code> function </code>, <code> mixin </code>, <code> variable </code>, либо <code> placeholder </code>). <br /> Если <code> {type} </code> является переменной <code> </code>, тогда знак <code> $ </code> перед именем переменной является необязательным. Наряду с знаком <code> $ </code> перед именем элемента, тип <code> {variable} </code> не является обязательным. <br /> Если <code> {type} </code> это <code> placeholder </code>, тогда знак <code>% </code> перед именем заполнителя является необязательным. Наряду с знаком <code>% </code> перед именем элемента, тип <code> {placeholder} </code> не является обязательным. </td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Описывает версию, в которой реализован или обновлен документируемый элемент </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> true </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, placeholders, variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Описание необязательно. Дефис перед значением является необязательным. <br /> Описание анализируется как  <code>markdown.*</code></td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Описывает ошибку, исключение вызываемую документированным элементом </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> true </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> <code> @throws </code>, <code> @exception </code> </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> true </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, placeholders </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Анализируется как <code>markdown.*</code></td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Описывает любые задачи на будущее, связанные с документируемым элементом </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> true </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> functions, mixins, placeholders, variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> Анализируется как <code>markdown.*</code></td>
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
       <th> Описание </th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td> Описание </td> 
       <td> Описывает тип документируемой переменной </td>
     </tr>
     <tr>
       <td> Многократное использование в одном документируемом элементе</td>
       <td> false </td>
     </tr>
     <tr>
       <td> Значение по умолчанию </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Псевдонимы </td>
       <td> - </td>
     </tr>
     <tr>
       <td> Автозаполнение </td>
       <td> false </td>
     </tr>
     <tr>
       <td> Допускаеться использовать в </td>
       <td> variables </td>
     </tr>
     <tr>
       <td> Дополнительные сведения </td>
       <td> При указании нескольких переменных, они должны быть разделены разделителем (<code> | </code>).</td>
     </tr>
   </tbody>
</table>

**[⬆ в начало](#оглавление)**