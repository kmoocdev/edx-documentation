.. _Developing Course Sections:

###################################
주제
###################################

주제를 만들기 전에, 우선 다음 사항을 이해해야 한다.

* :ref:`What Is a Section?`
* :ref:`Viewing Sections in the Outline`
* :ref:`The Student View of a Section`
* :ref:`Sections and Visibility to Students`
* :ref:`Release Statuses of Sections`

  
주제와 관련된 작업은 다음과 같은 것이 있다.

* :ref:`Create a Section`
* :ref:`Change a Section Name`
* :ref:`Set a Section Release Date`
* :ref:`Publish all Units in a Section`
* :ref:`Hide a Section from Students`
* :ref:`Delete a Section`


.. _What Is a Section?:

****************************
주제란?
****************************

주제는 강좌에서 가장 상위 범주에 해당한다. 순차적으로 공개되는 주제를 보면 개강일 이후 강좌가 진행되는 흐름을 알 수도 있고, 
강좌가 어떻게 구성되어 있는지를 한 눈에 볼 수 있기도 하다. 각 주제는 1개 이상의 소주제를 가진다.

.. _Viewing Sections in the Outline:

********************************
강좌 개요에서 주제 보기
********************************

다음 예시는 강좌개요에서 주제가 모두 접혀있는 상태를 보여준다.

.. image:: ../../../shared/building_and_running_chapters/Images/sections-outline.png
 :alt: Four sections in the outline

.. _The Student View of a Section:

******************************
학습자 화면에서 주제 보기 
******************************

학습자는 **강좌 내용** 탭에서 주제를 본다. 한 번에 1개의 주제씩 펼쳐볼 수 있다.
다음 예시에서 세 주제에 동그라미 표시가 되어있는데, 그중 세 번째 주제가 펼쳐진 상태로써 소주제를 볼 수 있게 되어 있다.

.. image:: ../../../shared/building_and_running_chapters/Images/sections_student.png
 :alt: The students view of the course with two sections circled

.. _Sections and Visibility to Students:

************************************************
주제 및 학습자 공개 설정
************************************************

주제의 공개일이 지정되지 않거나, 아직 그 날짜가 되지 않았다면 학습자는 주제에서 어떤 콘텐츠도 볼 수 없다. 

주제의 공개일이 지나야 학습자가 콘텐츠를 볼 수 있는데,

* 콘텐츠가 포함되어 있는 소주제의 공개일이 지났거나,
* 학습활동이 게시되었거나,
* 학습활동이 따로 학습자에게 비공개로 설정되어 있지 않은 경우 학습자가 볼 수 있다.

.. _Release Statuses of Sections:

************************************************
주제의 공개 상태
************************************************

강좌 개설자는 주제의 공개일을 조절할 수 있다. 콘텐츠를 학습자에게 공개하려면, 그 콘텐츠가 들어가 있는 주제가 공개되어야 한다. 주제의 공개 상태로는 다음과 같은 것이 있다.

* :ref:`Unscheduled`
* :ref:`Scheduled`
* :ref:`Released`
* :ref:`Released with Unpublished Changes`
* :ref:`Staff Only Content`

.. _Unscheduled:

========================
공개일이 지정되지 않음
========================

주제를 만든 후, ``1/1/2030 00:00:00 UTC`` 으로 기본값이 설정된 :ref:`강좌 시작일 설정하기<The Course Start Date>`를 바꾸지 않으면, 주제가 계속 ``공개일이 지정되지 않음`` 상태에 있게 된다. 이 상태에서는 학습자가 주제에 들어있는 콘텐츠를 볼 수 없음에 주의해야 한다. 

개강일을 변경하면, 주제 공개일의 기본값이 개강일로 바뀐다.

다음 예시는 공개일이 지정되지 않은 주제가 어떻게 강좌 개요에서 보이는지를 나타낸다. 

.. image:: ../../../shared/building_and_running_chapters/Images/section-unscheduled.png
 :alt: An unscheduled section

학습자가 콘텐츠를 볼 수 있게 하려면, 강좌 운영팀이 반드시 공개일을 지정해야 한다.

.. _Scheduled:

==========
예정됨
==========

공개가 예정된 주제는 지정된 공개일이 되기 전까지는 학습자에게 공개되지 않는다.
이는 그 주제 내부의 콘텐츠의 게시 상태와 관계 없는 것으로, 전체 주제가 학습자에게 공개되지 않는다면 콘텐츠 또한 학습자가 볼 수 없는 것이다. 

다음 예시는 공개가 예정된 주제가 어떻게 강좌 개요에서 보이는지를 나타낸다. 

.. image:: ../../../shared/building_and_running_chapters/Images/section-future.png
 :alt: An section scheduled to release in the future

주제의 공개 예정일이 지나야만 학습자가 볼 수 있다는 것에 유의해야 한다.

.. _Released:

===========================
공개됨
===========================

학습자는 공개된 주제를 보게 되지만, 그 주제 내부의 콘텐츠 중에서 공개된 소주제와 게시된 학습활동만 볼 수 있다.

다음 예시는 공개된 주제가 어떻게 강좌 개요에서 보이는지를 나타낸다.

.. image:: ../../../shared/building_and_running_chapters/Images/section-released.png
 :alt: An unscheduled section

.. _Released with Unpublished Changes:

==================================
공개 후 변경 사항은 아직 게시되지 않음
==================================

공개된 주제의 학습활동을 변경하였으나, 그것을 게시하지 않는 한 학습자들은 변경된 학습활동을 볼 수 없다. 

다음 예시는 게시되지 않은 학습활동이 포함된 주제가 어떻게 학습자에게 보이는지를 나타낸다.
게시되지 않은 학습활동은 그림에서 노란색으로 표시된 부분이다. 
또한 이 그림은 학습활동의 상태를 보기 위해 주제가 펼쳐진 상태이다.

.. image:: ../../../shared/building_and_running_chapters/Images/section-unpublished-changes.png
 :alt: A section with unpublished changes

학습자가 변경된 학습활동을 보려면, 강좌 운영팀이 반드시 해당 학습활동을 게시해야 한다.

.. _Staff Only Content:

===========================
강좌 운영팀에게만 공개
===========================

주제에 학습활동을 추가하되, 이것을 학습자에게는 비공개로 하여 강좌 운영팀만 볼 수 있도록 할 수 있다. 

이는 해당 학습활동을 포함하는 주제나 소주제의 공개 설정과는 관계 없이 적용되는 것이다.

다음 예시는 학습자에게는 비공개인 학습활동이 어떻게 강좌 개요에서 보이는지를 나타낸다.

.. image:: ../../../shared/building_and_running_chapters/Images/section-hidden-unit.png
 :alt: A section with a hidden unit 


.. _Create a Section:

****************************
주제 만들기
****************************

주제를 만든 후, ``1/1/2030 00:00:00 UTC`` 으로 기본값이 설정된 :ref:`강좌 시작일 설정하기<The Course Start Date>` 를 바꾸지 않으면, 주제가 계속 ``공개일이 지정되지 않음`` 상태에 있게 된다.

개강일을 변경하면, 주제 공개일의 기본값이 개강일로 바뀐다.

.. note:: 이미 개강하였다면, 새로 추가되는 주제는 즉시 학습자에게 보이게 된다. 

#. **신규 주제 추가하기** 를 클릭한다.
   
   .. image:: ../../../shared/building_and_running_chapters/Images/outline-create-section.png
     :alt: The outline with the New Section buttons circled

   그러면 기존의 콘텐츠 아래에 새로 추가한 주제가 추가될 것이다.

#. 신규 주제명을 입력한다. 학습자들은 이 주제명을 볼 것이다.

#. 이어서 :ref:`소주제 만들기<Create a Subsection>` 를 추가한다.
   
신규 주제를 추가한 후, :ref:`강좌 콘텐츠 시험해보기 <Testing Your Course
Content>` 를 권장한다.

.. _Change a Section Name:

********************************
주제명 바꾸기 
********************************

주제명 위에 마우스를 갖다대면 주제명 옆에 편집 아이콘이 나타날 것이다. 

.. image:: ../../../shared/building_and_running_chapters/Images/section-edit-icon.png
  :alt: The Edit Section Name icon

편집 아이콘을 클릭한다. 그러면 편집가능한 상태의 입력란이 생기게 된다. 
그곳에 새 이름을 입력하고 탭 키를 누르거나 입력란 바깥의 영역을 클릭하면 그 이름이 저장된다. 

 .. _Set a Section Release Date:

********************************
주제 공개일 설정하기
********************************

주제의 공개일을 설정하려면

#. 주제 영역에서 설정 아이콘을 클릭한다.
   
   .. image:: ../../../shared/building_and_running_chapters/Images/section-settings-box.png
    :alt: The section settings icon circled

   **설정** 대화 상자가 열릴 것이다.

#. 주제의 공개일시를 입력한다.
   
   .. image:: ../../../shared/building_and_running_chapters/Images/section-settings-release-date.png
    :alt: The section release date settings

#. **저장** 을 클릭한다.

:ref:`Release Dates` 에 더 자세한 안내가 나와있다.

.. _Publish all Units in a Section:

********************************
주제 내 전체 학습 활동 게시하기
********************************

주제 내 전체 학습 활동을 게시하려면 주제 영역의 게시 아이콘을 클릭해야 한다. 

.. image:: ../../../shared/building_and_running_chapters/Images/outline-publish-icon-section.png
 :alt: Publishing icon for a section

.. note:: 게시 아이콘은 새로 추가되거나 변경된 콘텐츠가 있을 때에만 나타난다.

학습자 공개 설정과 공개 상태에 관해 :ref:`Unit Publishing Status` 에 더 자세한 안내가 나와있다.

.. _Hide a Section from Students:

********************************
학습자에게 주제 감추기
********************************

소주제의 공개 상태와 관계 없이, 주제 내부의 전체 콘텐츠를 감출 수 있다.

학습자에게 주제를 감추려면,

#. 주제 영역의 게시 아이콘을 클릭한다. 
   
   .. image:: ../../../shared/building_and_running_chapters/Images/section-settings-box.png
    :alt: The section settings icon circled

   **설정** 대화 상자가 열릴 것이다.

#. **학습자에게 감추기** 의 체크박스를 클릭한다.

   .. image:: ../../../shared/building_and_running_chapters/Images/section-settings-hide.png
    :alt: The section hide from students setting

#. **저장** 을 클릭한다.

주제의 콘텐츠가 학습자에게 보이지 않을 것이다. 

학습자에게 주제를 공개하려면, 이 단계를 반복하되 **학습자에게 감추기** 의 체크박스를 해제한다.

.. note:: **학습자에게 감추기** 의 체크박스를 해제한다고 해서, 주제 내 콘텐츠 전체가 학습자에게 보이는 것은 아니다. 
 소주제나 학습활동 중 학습자에게 보이지 않게 설정해둔 것은 계속 그 상태가 유지된다. 


.. _Delete a Section:

********************************
주제 삭제하기
********************************

주제를 삭제하면, 해당 주제 내부의 전체 소주제와 학습활동도 함께 삭제된다.

.. note:: 주제를 삭제한 후에는 강좌 콘텐츠를 복구할 수 없다.  
나중에 필요할 수도 있다고 생각되는 콘텐츠는 삭제하지 말고, 비공개 주제에 옮겨두는 것을 권장한다.

주제를 삭제하려면

#. 삭제를 원하는 주제의 영역에 있는 삭제 아이콘을 클릭한다.

  .. image:: ../../../shared/building_and_running_chapters/Images/section-delete.png
   :alt: The section with Delete icon circled

2. 삭제를 확인하는 대화상자가 뜨면 **예, 주제를 삭제합니다.** 를 클릭한다.
