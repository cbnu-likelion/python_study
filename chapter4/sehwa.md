# 4�� ���� ũ����Ʈ : �ڵ� ����

> ### ���̽� �ڵ� ����ȭ�ϱ�


## 4.1 �ڸ�Ʈ �ޱ� : #

> '#' ���ڸ� �̿��Ͽ� �ڸ�Ʈ�� ǥ���Ѵ�. 


## 4.2 ���� �����ϱ� : \

> ���α׷��� �������� ����, \ ���ڸ� �̿��Ͽ� ������ �������� ������ �ۼ��Ѵ�.

## 4.3 ���ϱ� : if, elif, else

> ������ Ȯ���ϴ� ���̽��� ����

### 4.3.1 True�� False

## 4.4 �ݺ��ϱ� : while

> ���� ��Ŀ����

### 4.4.1 �ߴ��ϱ� : break

> �ݺ������� �ݺ����� �����ϰ� ���� �� 

### 4.4.2 �ǳʶٱ� : continue

> �ݺ������� ���� ������ �ǳʶٰ� ���� �� 

### 4.4.3 break Ȯ���ϱ� : else

> �ݺ������� break�� return �� �ݺ����� �����ϴ� ��ġ�� ������ else�� ����ȴ�. ( == break üĿ)

## 4.5 ��ȸ�ϱ� : for

> Iterable�� �ڷᱸ���� ��ȸ�ϴ� �ݺ���
> * C����� for���� �޸� ���� ������ ��ȸ������� ������ �� ������, �μ����� ���� i�� ����ϴ� ��� �ʿ��� ���� ��ü�� ��ȸ��Ų��. *

### 4.5.1 �ߴ��ϱ� : break

> �ݺ������� �ݺ����� �����ϰ� ���� ��

### 4.5.2 �ǳʶٱ� : continue

> �ݺ������� ���� ������ �ǳʶٰ� ���� �� 

### 4.5.3 break Ȯ���ϱ� : else

> �ݺ������� break�� return �� �ݺ����� �����ϴ� ��ġ�� ������ else�� ����ȴ�. ( == break üĿ)
> * ��� ���� ó���� ���� ���ִ� ��? *

### 4.5.4 ���� ������ ��ȸ�ϱ� : zip()

> for������ zip() �Լ��� ����Ͽ� ���� �������� ���ķ� ��ȸ�Ѵ�.

### 4.5.5 ���� ������ �����ϱ� : range()

> Ư�� ���� ������ �ڷᱸ���� �������� �ʰ��� ���� ��Ʈ���� ��ȯ�Ѵ�.
> ��ǻ�� �޸𸮸� ���� ������� �ʰ�, ���α׷� �浹 ���� ū ������ �����Ѵ�.

### 4.5.6 ��Ÿ ���ͷ�����

> ���� ������ ��ü�� ��ȸ �����ϰ� ���� �� �ִ�.

## 4.6 �������ڼ�

> �ϳ� �̻��� iterator�κ��� ���̽��� �ڷᱸ���� ����� ����Ʈ�� ���
> �ݺ����� �����׽�Ʈ�� ������ �� �ֵ��� ���ش�.

### 4.6.1 ����Ʈ ���������

> ** [ ǥ���� for �׸� in ��ȸ������ ��ü if ���� ] **
> ** [ ǥ���� for �׸� in ��ȸ������ ��ü for �׸� in ��ȸ ������ ��ü ] **

### 4.6.2 ��ųʸ� ���������

> ** [ Ű_ǥ���� : ��_ǥ���� for ǥ���� in ��ȸ ������ ��ü ] **

### 4.6.3 �� ���������

> ** [ ǥ���� for ǥ���� in ��ȸ ������ ��ü ] **

### 4.6.4 ���ʷ����� ���������

> ** [ ǥ���� for �׸� in ��ȸ������ ��ü if ���� ] **

## 4.7 �Լ�

> ���̽㿡�� �Լ��� ����Ͽ� �ڵ带 ���� �Ѵ�. 
> ��� Ÿ���� ���� �� �Է¹ް�, ��� Ÿ���� ���� �� ��ȯ�Ѵ�.
>
> #### �����ϱ�
> def �Լ� �̸�(�Է� �Ű�����) :
>
> #### ȣ���ϱ�
> �Լ� �̸�(����) :
> 
> ���ڴ� �ش� �Է� �Ű������� ����ȴ�.

### 4.7.1 ��ġ ����

> ���� �Է¹��� ������� �����ϴ� �Ű������� �����Ѵ�.
> ����, �� ��ġ�� �ǹ̸� �ƴ� ���� �߿��ϴ�.

### 4.7.2 Ű���� ����

> ��ġ ������ ȥ���� ���ϱ� ����, �Ű������� �����ϴ� �̸��� ���ڿ� �־� ������ �� �ִ�.
> ��ġ ���ڿ� Ű���� ���ڸ� �Լ��� ȣ���Ѵٸ� ��ġ ���ڰ� ���� �;� �Ѵ�.

### 4.7.3 �⺻ �Ű������� �����ϱ�

> ȣ���ڰ� �����ϴ� ���ڸ� �������� ������ �⺻���� ����Ѵ�.
> *�Լ��� ������ �� ���ȴ�. ���� �Ű������� �Լ��� ���� �� ������ ���� ����ȴ�. (p.133 ����)*

### 4.7.4 ��ġ ���� ������ : *

> ��ġ ���� �������� Ʃ�÷� ���´�.
> *������ ������ �������� �ʾƵ� �ȴ�.*

### 4.7.5 Ű���� ���� ������ : '**'

> Ű���� ���� �������� ��ųʸ��� ���´�.
> *������ ������ �������� �ʾƵ� �ȴ�.*
>
> #### ��ġ �Ű�����, '*'arg, '**'kwargs ������� ��ġ�Ѵ�.

### 4.7.6 docstring

> �Լ��� �������� ���� �Լ� ���� ��ü ���� �κп� ���ڿ��� ���Խ��� �Լ� ���ǿ� ������ ���� �� �ִ�.
> 
> - help(�Լ��̸�)
> - print(�Լ��̸�.__doc__)
> �� ���� Ȯ���� �� �ִ�.

### 4.7.7 �ϵ� �ù� : �Լ�

> ���̽㿡�� �Լ��� ��ü�̹Ƿ�
> - ������ �Ҵ�
> - �ٸ� �Լ����� ���ڷ� ���
> - �ٸ� �Լ����� ��ȯ
> �� �� �ִ�.
> *�̴� �Լ��� ����(�ڵ��� ����)�� �������� �� �޼��� �� �ְ� �Ѵ�.*

### 4.7.8 ���� �Լ�

> �Լ� �ȿ� �ٸ� �Լ��� ������ �� �ִ�.
> �̴� ������ �ڵ� �ߺ��� ���� �� �����ϰ� ����Ѵ�.

### 4.7.9 Ŭ����

> ���� �Լ��� Ŭ����ó�� �ൿ�� �� �ִ�.
> ���� �Լ��� ���Ե� �Լ����� ������ �������� �����ϰ�, �����Ѵ�.
> *__�Լ� �ܺ� ����, �Լ� ���� ����, ���� �Լ� ���ǰ� ��� �ٸ��� �� �� ��!__*

### 4.7.10 �͸� �Լ� : lambda()

> ���Ϲ����� ǥ���Ǵ� �͸� �Լ���.
> ���� ���� �Լ��� �����ϰ�, �̵��� ȣ���ؼ� ���� ������� ������ �� �����ϴ�.
> ex> lambda word: word.capitalize()

## 4.8 ���ʷ�����

> ���̽��� �������� �����ϴ� ��ü
> ��ǻ�� �޸𸮿� �����ϰ� ������ �ʿ� ���� ��ȸ�� �� �ְ� �Ѵ�.
> �Ϲ� �Լ��� �ٸ��� ���������� ȣ��� �׸��� ����ϰ�, ���� ���� ��ȯ�Ѵ�.
> (�Ϲ��Լ��� ���� ȣ�⿡ ���� �޸𸮰� ����, �׻� �Ȱ��� ���·� ù ���κ��� �����Ѵ�.)
>
> ���ʷ����� ��������ǿ� ���� �ڵ尡 �� ��쿡 ���ʷ����� �Լ��� ����Ѵ�.
> ���ʷ����� �Լ��� yield������ ���� ��ȯ�Ѵ�.


## 4.9 ��Ŀ������

> �ϳ��� �Լ��� ���ؼ� �� �ٸ� �Լ��� ��ȯ�ϴ� �Լ�
> �ҽ� �ڵ带 �ٲ��� �ʰ�, ����ϰ� �ִ� �Լ��� ������ �� ����Ѵ�.
> *�Լ� ��Ӱ� ����� ����������, ��Ŀ�����Ϳ� �� �ٸ� �Լ��� �и��Ǿ��ִ�.*
> ** @��Ŀ������_�̸�**
> ** �Լ� ���� **

# ���ͷ�����, ���ʷ�����
## ���ͷ�����
> ��ȸ / �ݺ� ������ ��ü
> #### ���ͷ����� vs ���ͷ���
> ���ͷ��� = �ݺ� ������ ��ü�� ���� ��ü
> ���ͷ����� = ���ͷ����� ��ȯ �����ϵ��� next()�� ���� ��ü


## ���ʷ�����
> ���ʷ����� = Ư���� ������ ���ͷ�����
> ** �ڷᱸ���� �޸𸮿� �������� �ʱ⿡, �޸� ȿ���� ����. **
> ��ü�� yield�� ��Ÿ���� ��� �Լ�


range() �� ���ʷ����͵� ���ͷ����͵� �ƴϴ�.

dir�� �� ����Ұ�!